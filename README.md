
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BoostMe</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #0d1117;
      color: #fff;
      font-family: 'Segoe UI', sans-serif;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      animation: fadein 0.8s ease;
    }

    h1 {
      font-size: 2.5rem;
      color: #00bfff;
      text-shadow: 0 0 15px #00bfff;
      margin-bottom: 10px;
    }

    p.slogan {
      font-size: 1.1rem;
      color: #aaa;
      margin-bottom: 30px;
      text-align: center;
    }

    .buttons {
      display: flex;
      flex-direction: column;
      gap: 15px;
      width: 80%;
      max-width: 300px;
    }

    .btn {
      background: transparent;
      border: 2px solid #00bfff;
      color: #00bfff;
      padding: 12px;
      font-size: 16px;
      font-weight: bold;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
      text-align: center;
      text-decoration: none;
    }

    .btn:hover {
      background: #00bfff;
      color: #000;
    }

    footer {
      position: absolute;
      bottom: 15px;
      font-size: 0.75rem;
      color: #555;
    }
 
    @keyframes fadein {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <h1>BoostMe</h1>
  <p class="slogan">Organize. Aja. Evolua.</p>

  <div class="buttons">
    <a href="login.html" class="btn">Entrar</a>
    <a href="cadastro.html" class="btn">Criar Conta</a>
  </div>

  <footer>BoostMe v1.0 — feito com café e energia azul</footer>

</body>
</html>
