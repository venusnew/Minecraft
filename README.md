<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minecraft</title>
    <script src="https://unpkg.com/@ruffle-rs/ruffle"></script>
    <script src="https://apis.google.com/js/platform.js"></script>   
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
        }
        ruffle-player {
            display: block;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <!-- Contenedor del juego -->
    <div class="game-container" id="gameContainer">
        <embed src="minecraft.swf" id="gameEmbed" width="100%" height="100%">
</body>
</html>
