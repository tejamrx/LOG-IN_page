# LOG-IN_page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    /* Add some basic styles to the page */
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
    }
    form {
      background-color: #fff;
      border-radius: 5px;
      padding: 20px;
      margin: 50px auto;
      max-width: 400px;
      box-shadow: 0px 2px 10px rgba(0,0,0,0.2);
    }
    input[type="text"], input[type="password"] {
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      width: 100%;
      margin-bottom: 20px;
    }
    input[type="submit"] {
      background-color: #4CAF50;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    input[type="submit"]:hover {
      background-color: #3e8e41;
    }
    .logo {
      text-align: center;
      margin-bottom: 20px;
    }
    .logo img {
      max-width: 200px;
    }
  </style>
</head>
<body>
  <div class="logo">
    <img src="https://example.com/logo.png" alt="Logo">
  </div>
  <form action="login.php" method="post">
    <h2>Login</h2>
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" placeholder="Enter your username" required>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required>
    <input type="submit" value="Login">
  </form>
</body>
</html>
