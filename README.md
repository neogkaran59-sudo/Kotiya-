<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Message For You</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffebee;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
            text-align: center;
        }

        .container {
            background: white;
            padding: 3rem;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            z-index: 10;
            max-width: 400px;
        }

        h1 { color: #d32f2f; margin-bottom: 1rem; }
        p { color: #555; font-size: 1.2rem; line-height: 1.5; }

        .buttons {
            margin-top: 2rem;
            display: flex;
            justify-content: space-around;
            gap: 10px;
        }

        button {
            padding: 12px 25px;
            font-size: 1rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: transform 0.2s;
        }

        #yesBtn { background-color: #ff4081; color: white; }
        
        /* The "No" button will move away when hovered */
        #noBtn { background-color: #9e9e9e; color: white; position: relative; }

        /* Floating Hearts Animation */
        .heart {
