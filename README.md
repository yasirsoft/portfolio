<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Div with JavaScript</title>
    <style>
        #colorBox {
            width: 200px;
            height: 200px;
            background-color: lightgray;
            border: 2px solid black;
            text-align: center;
            line-height: 200px;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <div id="colorBox">Click Me!</div>
    <script>
        const box = document.getElementById('colorBox');
        box.addEventListener('click', function() {
            this.style.backgroundColor = 'lightgreen';
            this.textContent = 'Clicked!';
        });
    </script>
</body>
</html>