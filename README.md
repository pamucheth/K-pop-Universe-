 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>K-Pop Haven</title>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-image: url("path/to/background.jpg"); /* Replace with your background image path */
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 20px;
      color: #fff;
    }

    h1 {
      text-align: center;
      font-size: 4em;
      margin-bottom: 20px;
    }

    /* Navigation Bar */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 30px;
    }

    nav a {
      text-decoration: none;
      color: #fff;
      padding: 10px 20px;
      font-weight: bold;
    }

    nav a:hover {
      color: #f0f0f0;
    }

    /* Featured Groups Section */
    .featured {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    .featured-group {
      width: calc(33% - 20px); /* Adjust for number of groups */
      margin-bottom: 20px;
      text-align: center;
    }

    .featured-group img {
      width: 100%;
      border-radius: 10px;
      opacity: 0.7;
      transition: opacity 0.3s;
    }

    .featured-group img:hover {
      opacity: 1;
    }

    .featured-group h3 {
      margin-top: 10px;
    }

    /* News Section */
    .news {
      margin-top: 50px;
      border-top: 1px solid rgba(255, 255, 255, 0.3);
      padding-top: 30px;
    }

    .news-article {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }

    .news-article img {
      width: 120px;
      height: 120px;
      margin-right: 20px;
      border-radius: 10px;
    }

    .news-article h4 {
      font-size: 1.2em;
      margin-bottom: 5px;
    }

    .news-article p {
      font-size: 0.9em;
      color: rgba(255, 255, 255, 0.7);
    }

    /* Social Media Links */
    .social-links {
      display: flex;
      justify-content: center;
      margin-top: 50px;
    }

    .social-links a {
      margin: 0 10px;
      color: #fff;
    }

    .social-links a:hover {
      color: #f0f0f0;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>K-Pop Haven</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Groups</a>
      <a href="#">News</a>
      <a href="#">About</a>
    </nav>

    <section class="featured">
      <div class="featured-group">
        <img src="path/to/group1.jpg" alt="Group 1">
        <h3>Group Name</h3>
      
