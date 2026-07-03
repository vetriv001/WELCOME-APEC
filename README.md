<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Welcome to APEC - Login</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    background:linear-gradient(135deg,#004080,#0073e6);
}

.container{
    width:380px;
    background:#fff;
    padding:35px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.3);
    text-align:center;
}

.logo{
    width:90px;
    margin-bottom:15px;
}

h1{
    color:#004080;
    margin-bottom:5px;
}

.subtitle{
    color:#666;
    margin-bottom:25px;
}

.input-group{
    margin-bottom:18px;
}

.input-group input{
    width:100%;
    padding:12px;
    border:1px solid #ccc;
    border-radius:8px;
    font-size:16px;
}

.input-group input:focus{
    border-color:#0073e6;
    outline:none;
}

button{
    width:100%;
    padding:12px;
    background:#0073e6;
    color:#fff;
    border:none;
    border-radius:8px;
    font-size:16px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#005bb5;
}

.options{
    display:flex;
    justify-content:space-between;
    margin-top:15px;
    font-size:14px;
}

.options a{
    text-decoration:none;
    color:#0073e6;
}

.options a:hover{
    text-decoration:underline;
}

.footer{
    margin-top:25px;
    font-size:12px;
    color:#888;
}
</style>

</head>
<body>

<div class="container">

    <!-- Replace with your own logo -->
    <img src="images/apec-logo.png" alt="APEC Logo" class="logo">

    <h1>WELCOME TO APEC</h1>
    <p class="subtitle">Please login to your account</p>

    <form action="#" method="post">

        <div class="input-group">
            <input type="text" name="username" placeholder="Username" required>
        </div>

        <div class="input-group">
            <input type="password" name="password" placeholder="Password" required>
        </div>

        <button type="submit">Login</button>

        <div class="options">
            <label>
                <input type="checkbox"> Remember Me
            </label>

            <a href="#">Forgot Password?</a>
        </div>

    </form>

    <div class="footer">
        © 2026 APEC. All Rights Reserved.
    </div>

</div>

</body>
</html>
