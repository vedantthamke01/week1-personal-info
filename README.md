<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Personal Information Manager</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f4f6f8;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: auto;
            background: #ffffff;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        h1, h2 {
            color: #2c3e50;
        }

        h1 {
            text-align: center;
        }

        ul {
            margin-left: 20px;
        }

        code, pre {
            background: #eee;
            padding: 10px;
            border-radius: 5px;
            display: block;
            overflow-x: auto;
        }

        .sample-output {
            background: #111;
            color: #0f0;
            font-family: monospace;
            padding: 15px;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9em;
            color: #666;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>🗂️ Personal Information Manager</h1>

    <p>
        A simple Python program that stores, processes, and displays personal
        information in a clean, formatted way. This project is designed as a
        beginner-friendly introduction to Python fundamentals.
    </p>

    <h2>🚀 Project Overview</h2>
    <p>
        The <strong>Personal Information Manager</strong> allows users to store
        basic personal details, enter additional information dynamically, and
        view everything neatly formatted in the terminal.
    </p>

    <h2>🧠 What I Learned</h2>
    <ul>
        <li>Variables – Storing different types of data</li>
        <li>Input & Output – Taking user input and displaying results</li>
        <li>String Formatting – Using f-strings</li>
        <li>Error Handling – Basic input validation</li>
        <li>Simple Calculations – Converting age from years to months</li>
    </ul>

    <h2>✨ Features</h2>
    <ul>
        <li>Stores static information (name, age, city, hobby)</li>
        <li>Gets dynamic input (favorite food, favorite color)</li>
        <li>Displays information in a formatted layout</li>
        <li>Calculates age in months</li>
        <li>Basic input validation</li>
    </ul>

    <h2>🖥️ Sample Output</h2>
    <div class="sample-output">
        ===================================<br>
             PERSONAL INFORMATION<br>
        ===================================<br>
        Name: Vedant Thamke<br>
        Age: 19 (228 months old)<br>
        City: Nagpur<br>
        Hobby: Drawing<br><br>
        Favorite Food: Apple<br>
        Favorite Color: Blue<br>
        ===================================<br>
        Thank you for using the program!
    </div>

    <h2>🛠️ How to Run the Program</h2>
    <ol>
        <li>Make sure Python is installed</li>
        <li>Open terminal / command prompt</li>
        <li>Navigate to the project folder</li>
        <li>Run:
            <pre>python personal_info.py</pre>
        </li>
        <li>Follow the prompts</li>
    </ol>

    <h2>📁 File Structure</h2>
    <pre>
Personal-Information-Manager/
│
├── personal_info.py
└── README.md
    </pre>

    <h2>🎯 Future Improvements</h2>
    <ul>
        <li>Save data to a file (JSON or text)</li>
        <li>Support multiple users</li>
        <li>Add a menu-based interface</li>
        <li>Improve validation</li>
        <li>Build a GUI version</li>
    </ul>

    <footer>
        Built as a first Python project by Vedant Thamke 🚀
    </footer>

</div>

</body>
</html>
