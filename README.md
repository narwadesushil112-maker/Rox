<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #6e8efb, #a777e3);
    }

    .login-box {
      width: 350px;
      background: #fff;
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
    }

    .login-box h2 {
      text-align: center;
      margin-bottom: 30px;
      color: ;
    }

    .input-box {
      position: relative;
      margin-bottom: 25px;
    }

    .input-box input {
      width: 100%;
      padding: 10px 15px;
      border: 2px solid #ccc;
      border-radius: 8px;
      outline: none;
      font-size: 16px;
      transition: 0.3s;
    }

    .input-box input:focus {
      border-color: #6e8efb;
    }

    .login-box a {
      display: block;
      text-align: right;
      color: ;
      font-size: 14px;
      text-decoration: none;
      margin-bottom: 20px;
      transition: 0.3s;
    }

    .login-box a:hover {
      text-decoration: underline;
    }

    .btn {
      width: 100%;
      padding: 10px;
      border: none;
      background: blue;
      color: #fff;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #5a77e0;
    }

    .register-link {
      text-align: center;
      margin-top: 20px;
      font-size: 14px;
      color: #555;
    }

    .register-link a {
      color: #6e8efb;
      text-decoration: none;
      font-weight: 600;
    }

    .register-link a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="login-box">
    <h2>Login into taj.</h2>
    <form>
      <div class="input-box">
        <input type="text" placeholder="Username" required>
      </div>

      <div class="input-box">
        <input type="password" placeholder="Password" required>
      </div>

      <a href="#">Forgot Password?</a>

      <button type="submit" class="btn">Login</button>

      <div class="register-link">
        Not a member? <a href="#">Sign up</a>
      </div>
    </form>
  </div>

</body>
</html>
