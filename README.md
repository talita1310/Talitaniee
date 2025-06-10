<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Register - talita Media Sosial</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background: linear-gradient(to right, #74ebd5, #ACB6E5);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .container {
      background-color: white;
      padding: 30px 40px;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      max-width: 400px;
      width: 100%;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }
    label {
      display: block;
      margin-bottom: 5px;
      font-weight: 600;
    }
    input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 14px;
    }
    button {
      width: 100%;
      padding: 12px;
      background-color: #007bff;
      border: none;
      border-radius: 8px;
      color: white;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Registrasi web talita</h2>
    <form onsubmit="return registerUser()">
      <label for="Username">Username:</label>
      <input type="text" id="username" required>

      <label for="password">Password:</label>
      <input type="password" id="password" required>

      <label for="confirm-password">Konfirmasi Password:</label>
      <input type="password" id="confirm-password" required>

      <button type="submit">Register</button>
    </form>
  </div>

  <script>
    function registerUser() {
      const username = document.getElementById("username").value;
      const password = document.getElementById("password").value;
      const confirmPassword = document.getElementById("confirm-password").value;

      if (password !== confirmPassword) {
        alert("Password dan konfirmasi password tidak cocok!");
        return false;
      }

      localStorage.setItem("username", username);
      window.location.href = "ye.html";
      return false;
    }
  </script>
</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>talita saron Purnomo</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link ke file CSS untuk styling -->
    <style>
        body {
            font-family: tlita, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            margin: 0;
        }
        .post-form {
            margin-bottom: 20px;
        }
        .post-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            resize: none;
        }
        .post {
            border-top: 1px solid #ccc;
            padding: 10px 0;
        }
        .post img {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
        }
    </style>
</head>
<body>
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>talita saron Purnomo</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link ke file CSS untuk styling -->
    <style>
        body {
            font-family: tlita, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            margin: 0;
        }
        .post-form {
            margin-bottom: 20px;
        }
        .post-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            resize: none;
        }
        .post {
            border-top: 1px solid #ccc;
            padding: 10px 0;
        }
        .post img {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
        }
    </style>
</head>
<body>
<header>
	<marquee width="600" height="40">talita saron purnomo</marquee>
	<h1>talita kacaw  </h1>
    <p>Beranda Profil Pesan</p>
</header>
<div class="container">
    <h2>Beranda</h2>
    
    <div class="post-form">
        <label for="postText">Buat Postingan</label>
        <select id="postType">
            <option value="text">Teks</option> <option value="gambar">gambar</option>
        </select>
        <textarea id="postText" rows="4" placeholder="Tulis sesuatu..."></textarea>
        <button type="button">Posting</button>
    </div>

    <div class="post">
        <strong>reem</strong><br>
        <small>2025-06-05 15:14</small>
        <p></p>
        <img src="talita.jpg" alt="talita">
     <div class="like-section">
         <button class="like-button" onclick="toggleLike(this)">
         <span class="like-icon">&#x1F49A;</span> <!-- Ikon suka (Anda bisa menggunakan font awesome atau icon set lain) -->
         <span class="like-count">140</span>
            </button>
    </div>
</head>
<body>
<header>
    <h1> Thank you for everything  </h1>	

</div>
</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>talita saron Purnomo</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link ke file CSS untuk styling -->
    <style>
        body {
            font-family: tlita, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            margin: 0;
        }
        .post-form {
            margin-bottom: 20px;
        }
        .post-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            resize: none;
        }
        .post {
            border-top: 1px solid #ccc;
            padding: 10px 0;
        }
        .post img {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
        }
    </style>
</head>
<body>
<header>
	<marquee width="600" height="40">talita saron purnomo</marquee>
	<h1>talita kacaw  </h1>
    <p>Beranda Profil Pesan</p>
</header>
<div class="container">
    <h2>Beranda</h2>
    
    <div class="post-form">
        <label for="postText">Buat Postingan</label>
        <select id="postType">
            <option value="text">Teks</option> <option value="gambar">gambar</option>
        </select>
        <textarea id="postText" rows="4" placeholder="Tulis sesuatu..."></textarea>
        <button type="button">Posting</button>
    </div>

    <div class="post">
        <strong>reem</strong><br>
        <small>2025-06-05 15:14</small>
        <p></p>
        <img src="talita.jpg" alt="talita">
     <div class="like-section">
         <button class="like-button" onclick="toggleLike(this)">
         <span class="like-icon">&#x1F49A;</span> <!-- Ikon suka (Anda bisa menggunakan font awesome atau icon set lain) -->
         <span class="like-count">140</span>
            </button>
    </div>
</head>
<body>
<header>
    <h1> Thank you for everything  </h1>	

</div>
</body>
</html>
