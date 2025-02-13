<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Will You Be My Valentine? ❤️</h1>
        <div class="buttons">
            <a href="yes.html" class="btn yes">Yes</a>
            <button class="btn no" onclick="moveButton()">No</button>
        </div>
    </div>

    <script>
        function moveButton() {
            const button = document.querySelector(".no");
            button.style.position = "absolute";
            button.style.left = Math.random() * window.innerWidth + "px";
            button.style.top = Math.random() * window.innerHeight + "px";
        }
    </script>
</body>
</html>
