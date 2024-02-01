# varshmello.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f7f7f7;
        }

        .question-container {
            text-align: center;
        }

        #no-option {
            display: inline-block;
            transition: transform 0.3s ease-in-out;
        }

        #no-option:hover {
            transform: translateX(-10px);
        }
    </style>
    <title>Cute Question</title>
</head>
<body>

<div class="question-container">
    <h1>Will you say "Yes"?</h1>
    <p>
        <span id="yes-option">Yes</span> /
        <span id="no-option">No</span>
    </p>
</div>

</body>
</html>
