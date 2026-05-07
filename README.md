<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Video App</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f9f9f9;
}

/* Header */
.header {
  background: #ff0000;
  color: white;
  padding: 15px;
  text-align: center;
  font-size: 20px;
  position: sticky;
  top: 0;
}

/* Video List */
.video-list {
  padding: 10px;
}

/* Video Card */
.video-card {
  background: white;
  margin-bottom: 15px;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

/* Thumbnail */
.thumbnail {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

/* Content */
.video-info {
  padding: 10px;
}

.video-title {
  font-size: 16px;
  font-weight: bold;
  margin: 0;
}

.watch-btn {
  display: inline-block;
  margin-top: 8px;
  padding: 6px 12px;
  background: #ff0000;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-size: 14px;
}

/* Bottom Navigation */
.bottom-nav {
  position: fixed;
  bottom: 0;
  width: 100%;
  background: white;
  display: flex;
  justify-content: space-around;
  padding: 10px 0;
  box-shadow: 0 -2px 6px rgba(0,0,0,0.1);
}

.nav-item {
  text-align: center;
  font-size: 12px;
  color: #555;
}

.nav-item:hover {
  color: red;
}
</style>

</head>

<body>

<div class="header">My Video App</div>

<div class="video-list">

  <!-- Video 1 -->
  <div class="video-card">
    <img class="thumbnail" src=""C:\Users\himam\Downloads\org.jpeg"">
    <div class="video-info">
      <p class="video-title">My First Video</p>
      <a class="watch-btn" href="https://youtu.be/lRyXlvIJFWI?si=qqHx0xMz1Y6xPyjG" target="_blank">▶ Watch</a>
    </div>
  </div>

  <!-- Video 2 -->
  <div class="video-card">
    <img class="thumbnail" src=""C:\Users\himam\Downloads\comp.jpg"">
    <div class="video-info">
      <p class="video-title">My Second Video</p>
      <a class="watch-btn" href="https://youtu.be/mDIVpJgjoXQ?si=_DtfR_XbRwJZTxfU" target="_blank">▶ Watch</a>
    </div>
  </div>

  <!-- Video 3 -->
  <div class="video-card">
    <img class="thumbnail" src=""C:\Users\himam\Downloads\seas.jpg"">
    <div class="video-info">
      <p class="video-title">My Third Video</p>
      <a class="watch-btn" href="https://youtu.be/26qTgXJKMAE?si=vhGe-cMIqCHr45mh" target="_blank">▶ Watch</a>
    </div>
  </div>

</div>

<!-- Bottom Navigation -->
<div class="bottom-nav">
  <div class="nav-item">🏠 Home</div>
  <div class="nav-item">🔥 Trending</div>
  <div class="nav-item">📂 Library</div>
</div>

</body>
</html>
