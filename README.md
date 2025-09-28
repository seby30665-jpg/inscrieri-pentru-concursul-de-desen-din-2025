<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <title>Inscrieri pentru concursul de desen din 2025</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
    #text { margin-top: 20px; font-size: 20px; color: #186db0; }
    button { padding: 10px 20px; font-size: 16px; background: #186db0; color: #fff; border: none; border-radius: 5px; cursor: pointer; }
    button:active { background: #144e7a; }
    a { display: block; margin-top: 40px; color: #186db0; }
  </style>
</head>
<body>
  <h1>Inscrieri pentru concursul de desen din 2025</h1>
  <button onclick="afiseazaText()">Inscrie-te aici</button>
  <div id="text"></div>
  <!-- Exemplu de link (îl poți modifica după ce publici site-ul)
  <a href="https://exemplu.com/proiectul-tau" target="_blank">Accesează site-ul aici</a>
  -->
  <script>
    function afiseazaText() {
      document.getElementById('text').innerText = 'Ai fost inscris';
    }
  </script>
</body>
</html>
