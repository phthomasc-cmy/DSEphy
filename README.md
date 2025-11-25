<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Chan Physics Lab</title>
    <style>
        /* --- General Page Styles --- */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #1a1a2e; /* Dark Blue Background */
            color: #ffffff;
            margin: 0;
            padding: 20px;
        }

        /* --- Header Styles --- */
        header {
            text-align: center;
            padding: 40px 0;
            margin-bottom: 30px;
            background: linear-gradient(90deg, #ff00cc, #333399); /* Colorful Gradient */
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
        }

        h1 {
            font-size: 3em;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        p.subtitle {
            font-size: 1.2em;
            opacity: 0.9;
        }

        /* --- Grid Layout for Chapters --- */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* --- Chapter Card Styles --- */
        .chapter-card {
            background-color: #16213e;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            transition: transform 0.3s ease;
            border: 1px solid #2a2a4e;
        }

        .chapter-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.5);
        }

        .card-header {
            padding: 15px;
            text-align: center;
            font-weight: bold;
            font-size: 1.4em;
            color: white;
        }

        /* --- Individual Colors for Chapters --- */
        .ch1 .card-header { background: linear-gradient(45deg, #ff416c, #ff4b2b); } /* Red */
        .ch2 .card-header { background: linear-gradient(45deg, #f7971e, #ffd200); } /* Orange/Yellow */
        .ch3 .card-header { background: linear-gradient(45deg, #56ab2f, #a8e063); } /* Green */
        .ch4 .card-header { background: linear-gradient(45deg, #11998e, #38ef7d); } /* Teal */
        .ch5 .card-header { background: linear-gradient(45deg, #00b09b, #96c93d); } /* Mint */
        .ch6 .card-header { background: linear-gradient(45deg, #2193b0, #6dd5ed); } /* Blue */
        .ch7 .card-header { background: linear-gradient(45deg, #3a1c71, #d76d77, #ffaf7b); } /* Purple/Pink */
        .ch8 .card-header { background: linear-gradient(45deg, #8e2de2, #4a00e0); } /* Deep Purple */
        .ch9 .card-header { background: linear-gradient(45deg, #ec008c, #fc6767); } /* Pink */

        /* --- Link Slots Styles --- */
        .links-container {
            padding: 20px;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .sim-link {
            display: block;
            text-decoration: none;
            color: #fff;
            background-color: #0f3460;
            padding: 12px;
            text-align: center;
            border-radius: 8px;
            transition: background 0.2s;
            border: 1px solid #1f4068;
        }

        .sim-link:hover {
            background-color: #e94560; /* Highlight color on hover */
            font-weight: bold;
        }

        /* --- Footer --- */
        footer {
            text-align: center;
            margin-top: 50px;
            color: #666;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Mr. Chan Physics Lab</h1>
        <p class="subtitle">Interactive Simulations & Experiments</p>
    </header>

    <div class="container">

        <!-- Chapter 1 -->
        <div class="chapter-card ch1">
            <div class="card-header">Chapter 1</div>
            <div class="links-container">
                <a href="#" class="sim-link">1.1 Simulation Name</a>
                <a href="#" class="sim-link">1.2 Simulation Name</a>
                <a href="#" class="sim-link">1.3 Simulation Name</a>
                <a href="#" class="sim-link">1.4 Simulation Name</a>
                <a href="#" class="sim-link">1.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 2 -->
        <div class="chapter-card ch2">
            <div class="card-header">Chapter 2</div>
            <div class="links-container">
                <a href="#" class="sim-link">2.1 Simulation Name</a>
                <a href="#" class="sim-link">2.2 Simulation Name</a>
                <a href="#" class="sim-link">2.3 Simulation Name</a>
                <a href="#" class="sim-link">2.4 Simulation Name</a>
                <a href="#" class="sim-link">2.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 3 -->
        <div class="chapter-card ch3">
            <div class="card-header">Chapter 3</div>
            <div class="links-container">
                <a href="#" class="sim-link">3.1 Simulation Name</a>
                <a href="#" class="sim-link">3.2 Simulation Name</a>
                <a href="#" class="sim-link">3.3 Simulation Name</a>
                <a href="#" class="sim-link">3.4 Simulation Name</a>
                <a href="#" class="sim-link">3.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 4 -->
        <div class="chapter-card ch4">
            <div class="card-header">Chapter 4</div>
            <div class="links-container">
                <a href="#" class="sim-link">4.1 Simulation Name</a>
                <a href="#" class="sim-link">4.2 Simulation Name</a>
                <a href="#" class="sim-link">4.3 Simulation Name</a>
                <a href="#" class="sim-link">4.4 Simulation Name</a>
                <a href="#" class="sim-link">4.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 5 -->
        <div class="chapter-card ch5">
            <div class="card-header">Chapter 5</div>
            <div class="links-container">
                <a href="#" class="sim-link">5.1 Simulation Name</a>
                <a href="#" class="sim-link">5.2 Simulation Name</a>
                <a href="#" class="sim-link">5.3 Simulation Name</a>
                <a href="#" class="sim-link">5.4 Simulation Name</a>
                <a href="#" class="sim-link">5.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 6 -->
        <div class="chapter-card ch6">
            <div class="card-header">Chapter 6</div>
            <div class="links-container">
                <a href="#" class="sim-link">6.1 Simulation Name</a>
                <a href="#" class="sim-link">6.2 Simulation Name</a>
                <a href="#" class="sim-link">6.3 Simulation Name</a>
                <a href="#" class="sim-link">6.4 Simulation Name</a>
                <a href="#" class="sim-link">6.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 7 -->
        <div class="chapter-card ch7">
            <div class="card-header">Chapter 7</div>
            <div class="links-container">
                <a href="#" class="sim-link">7.1 Simulation Name</a>
                <a href="#" class="sim-link">7.2 Simulation Name</a>
                <a href="#" class="sim-link">7.3 Simulation Name</a>
                <a href="#" class="sim-link">7.4 Simulation Name</a>
                <a href="#" class="sim-link">7.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 8 -->
        <div class="chapter-card ch8">
            <div class="card-header">Chapter 8</div>
            <div class="links-container">
                <a href="#" class="ai_studio_code (24).html">Rate of Conduction</a>
                <a href="#" class="sim-link">8.2 Simulation Name</a>
                <a href="#" class="sim-link">8.3 Simulation Name</a>
                <a href="#" class="sim-link">8.4 Simulation Name</a>
                <a href="#" class="sim-link">8.5 Simulation Name</a>
            </div>
        </div>

        <!-- Chapter 9 -->
        <div class="chapter-card ch9">
            <div class="card-header">Chapter 9</div>
            <div class="links-container">
                <a href="#" class="sim-link">9.1 Simulation Name</a>
                <a href="#" class="sim-link">9.2 Simulation Name</a>
                <a href="#" class="sim-link">9.3 Simulation Name</a>
                <a href="#" class="sim-link">9.4 Simulation Name</a>
                <a href="#" class="sim-link">9.5 Simulation Name</a>
            </div>
        </div>

    </div>

    <footer>
        &copy; 2023 Mr. Chan Physics Lab. All rights reserved.
    </footer>

</body>
</html>
