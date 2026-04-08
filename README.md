# KKEKKE
KKEKKE PASTELERÍA
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Compra completada</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f2f2f2;
      padding-top: 100px;
    }

    .box {
      background: white;
      padding: 30px;
      margin: auto;
      width: 320px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    h1 {
      color: #2ecc71;
    }

    button {
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      background-color: #3498db;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #2980b9;
    }
  </style>
</head>

<body>

  <div class="box">
    <h1>🎉 ¡Compra completada!</h1>

    <p>😳 Espera...</p>
    <p>No hay ningún producto 😂</p>
    <p>Pero hiciste clic sin pensarlo</p>

    <p><strong>Nivel de comprador:</strong> IMPULSIVO PRO 💸</p>

    <br>

    <button onclick="volver()">Volver a intentarlo</button>
  </div>

  <script>
    function volver() {
      window.location.href = "https://sites.google.com/view/TU-PAGINA";
    }

    // Mensaje troll automático 😈
    setTimeout(() => {
      alert("Dona va");
    }, 1500);
  </script>

</body>
</html>
