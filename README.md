<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <meta name="keywords" content="Gerador de senhas"> <link rel="stylesheet" href="style.css"> Gerador de senha </head> <body>
<img class="logo" src=". assets/logo.png" alt="Gerador senha logo"/>
<div class="container-input">
<span>  <span id="valor"></span>
<input id="slider" class="slider" type="range" min="5" max="25" value="15"/>
<button id="button" class="button-cta" onclick="generatePassword ()">Gerar senha</button>
</div>
<div id="container-password" onclick="copyPassword ()" class="container-password hide">
<span class="title">Sua senha gerada foi:</span>
<span id="password" class="password"></span>
<span class="tooltip">Clique na senha para copiar. </span>
</div>

</body>
</html>
