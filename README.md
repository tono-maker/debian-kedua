












































<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>NCC Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background: #0f172a;
            color: white;
        }
        /* Navbar */
        nav {
            background: #020617;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav h2 {
            color: #38bdf8;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav ul li {
            cursor: pointer;
            transition: 0.3s;
        }

        nav ul li:hover {
            color: #38bdf8;
        }

        /* Hero */
        .hero {
            height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }

        .logo {
            font-size: 80px;
            font-weight: bold;
            border: 4px solid #38bdf8;
            padding: 30px 70px;
            border-radius: 15px;
            box-shadow: 0 0 20px #38bdf8;
            margin-bottom: 20px;
        }

        /* Section */
        section {
            padding: 60px 30px;
            text-align: center;
        }

        .card {
            background: #020617;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            display: inline-block;
            width: 250px;
        }

        .card:hover {
            box-shadow: 0 0 15px #38bdf8;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #020617;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav>
        <h2>NCC</h2>
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Team</li>
            <li>Contact</li>
        </ul>
    </nav>

    <!-- Hero -->
    <div class="hero">
        <div class="logo">NCC</div>
        <p>Welcome to NCC Cyber Community</p>
    </div>

    <!-- About -->
    <section>
        <h2>About NCC</h2>
        <p>Kami adalah komunitas cyber security & teknologi.</p>
    </section>

    <!-- Team -->
    <section>
        <h2>Our Team</h2>
        <div class="card">D4vi1d Cyber</div>
        <div class="card">Ri1FF4t Cyber</div>
    </section>

    <!-- Contact -->
    <section>
        <h2>Contact</h2>
        <p>Email: ncc@gmail.com</p>
        <p>Phone Number: 081234567890</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 NCC</p>
    </footer>

</body>
</html>
