  LOCAL WAY TO CONNECT BOOTSTRAP WITH PACKAGE MANAGER

//=============================================
TERMINAL

npm i bootstrap@5.3.2 

npm i bootstrap-icons


HTML
  <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
      LINKS CSS BOOSTRAP FUNCTIONALITY
  <link rel="stylesheet" href="node_modules/bootstrap-icons/font/bootstrap-icons.css";">
    LINKS BOOTSTRAP ICONS    
  <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
      LINKS CSS BOOSTRAP FUNCTIONALITY
  
//=============================================

ADDING GOOGLE FONTS

what is the best way to add fonts ? directly to css or sass ?
Ill choose adding directly to css for now 

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inconsolata:wght@500;700&family=Libre+Franklin:wght@300;600;700&display=swap" rel="stylesheet">
  <style>
  @import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@500;700&family=Libre+Franklin:wght@300;600;700&display=swap');
  body {font-family: 'Inconsolata', monospace;}
  </style>

//=============================================
SO HEAD STAY THIS
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="node_modules/bootstrap-icons/font/bootstrap-icons.css";">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inconsolata:wght@500;700&family=Libre+Franklin:wght@300;600;700&display=swap" rel="stylesheet">
  <style>
  @import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@500;700&family=Libre+Franklin:wght@300;600;700&display=swap');
  body {font-family: 'Inconsolata', monospace;}
  </style>
  <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script> 
  <title>Frontend Mentor | Ping coming soon page | Lotso' Coffee Co.</title>
</head>
