<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja de Perfis Instagram</title>
  <style>
    /* RESET */
    * {margin:0; padding:0; box-sizing:border-box; font-family: 'Arial', sans-serif;}
    body {background-color: #e6f0fa; color: #333;}

    /* CONTAINER */
    .container {max-width: 1200px; margin: 0 auto; padding: 20px;}

    /* HEADER */
    header {text-align: center; padding: 40px 0; background-color: #cce4ff; border-bottom: 2px solid #99c2ff;}
    header h1 {font-size: 2.5rem; color: #007acc;}

    /* LOGIN */
    .login-box {max-width: 400px; margin: 30px auto; background-color: #ffffff; padding: 30px; border-radius: 10px; box-shadow: 0 0 20px rgba(0,0,0,0.1);}
    .login-box h2 {text-align: center; margin-bottom: 20px; color: #007acc;}
    .login-box input {width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #99c2ff; border-radius: 5px;}
    .login-box button {width: 100%; padding: 10px; background-color: #007acc; color: #fff; border: none; border-radius: 5px; cursor: pointer; font-size: 1rem; transition: background 0.3s;}
    .login-box button:hover {background-color: #005f99;}

    /* STORE */
    .store {margin-top: 50px;}
    .store h2 {text-align: center; margin-bottom: 30px; color: #007acc;}
    .products {display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;}
    .product {background-color: #ffffff; padding: 20px; border-radius: 10px; width: 300px; box-shadow: 0 0 15px rgba(0,0,0,0.1); display: flex; flex-direction: column; align-items: center; transition: transform 0.3s;}
    .product:hover {transform: translateY(-5px);}
    .product img {width: 100px; border-radius: 50%; margin-bottom: 15px;}
    .product h3 {margin-bottom: 10px; color: #007acc;}
    .product p {margin-bottom: 15px; text-align: center;}
    .product button {padding: 10px 20px; background-color: #007acc; color: #fff; border: none; border-radius: 5px; cursor: pointer; transition: background 0.3s;}
    .product button:hover {background-color: #005f99;}

    /* FOOTER */
    footer {text-align: center; margin-top: 50px; padding: 20px; background-color: #cce4ff; border-top: 2px solid #99c2ff;}

  </style>
</head>
<body>
  <header>
    <h1>Instagram Profiles Store</h1>
  </header>

  <div class="container">

    <!-- LOGIN -->
    <div class="login-box" id="loginBox">
      <h2>Login</h2>
      <input type="text" id="username" placeholder="Usuário">
      <input type="password" id="password" placeholder="Senha">
      <button onclick="login()">Entrar</button>
      <p id="loginError" style="color:red; text-align:center; margin-top:10px; display:none;">Usuário ou senha incorretos!</p>
    </div>

    <!-- STORE -->
    <div class="store" id="store" style="display:none;">
      <h2>Perfis à Venda</h2>
      <div class="products">
        <div class="product">
          <img src="https://via.placeholder.com/100" alt="Perfil 1">
          <h3>Perfil 1</h3>
          <p>Mais de 800 seguidores</p>
          <p>Preço: R$46</p>
          <button onclick="buy('Perfil 1', 46)">Comprar</button>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/100" alt="Perfil 2">
          <h3>Perfil 2</h3>
          <p>Mais de 800 seguidores</p>
          <p>Preço: R$60</p>
          <button onclick="buy('Perfil 2', 60)">Comprar</button>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/100" alt="Perfil 3">
          <h3>Perfil 3</h3>
          <p>Mais de 800 seguidores</p>
          <p>Preço: R$91</p>
          <button onclick="buy('Perfil 3', 91)">Comprar</button>
        </div>
      </div>
    </div>

  </div>

  <footer>
    <p>&copy; 2025 Instagram Profiles Store. Todos os direitos reservados.</p>
  </footer>

  <script>
    // LOGIN SIMPLES
    function login() {
      const username = document.getElementById('username').value;
      const password = document.getElementById('password').value;
      const loginBox = document.getElementById('loginBox');
      const store = document.getElementById('store');
      const error = document.getElementById('loginError');

      // Usuário e senha hardcoded apenas para demo
      if(username === 'usuario' && password === 'senha123') {
        loginBox.style.display = 'none';
        store.style.display = 'block';
        error.style.display = 'none';
      } else {
        error.style.display = 'block';
      }
    }

    // FUNÇÃO DE COMPRA SIMULADA
    function buy(profile, price) {
      alert(`Você selecionou ${profile} por R$${price}.`);
    }

  </script>
</body>
</html>
