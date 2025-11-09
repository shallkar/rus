[сайт.html](https://github.com/user-attachments/files/23439835/default.html)
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>ЧЕ ТАМ</title>

  <!-- Подключаем шрифт Metal Mania -->
  <link href="https://fonts.googleapis.com/css2?family=Metal+Mania&display=swap" rel="stylesheet">

  <style>
    body {
      background-color: #111;
      color: #e00;
      text-align: center;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      margin: 0;
      font-family: 'Metal Mania', cursive;
    }

    h1 {
      font-size: 70px;
      text-shadow: 4px 4px 10px black, 0 0 20px red;
      letter-spacing: 3px;
      text-transform: uppercase;
    }
    button {
      font-size: 25px;      
      padding: 10px 20px;
      background-color: #0078ff;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    /* Анимация лёгкого пульса */
    @keyframes pulse {
      0% { text-shadow: 4px 4px 10px black, 0 0 20px red; }
      50% { text-shadow: 4px 4px 20px black, 0 0 40px #ff3333; }
      100% { text-shadow: 4px 4px 10px black, 0 0 20px red; }
    }

    h1 {
      animation: pulse 1.5s infinite;
    }
  </style>
</head>

<body>
  <h1>ЧЕ ТАМ ?</h1>
  <button onclick="document.getElementById('popup').style.display='block'">
  Нажми сюда
</button>
  <div id="popup" style="display:none;
                       background-color:#111;  
                       padding:20px;
                       width:250px;
                       font-size:24px;
                       margin:20px auto;
                       text-align:center;">
  Ехала ?
</div>
</body>
</html>
