# index.html<!DOCTYPE html>
<html>
<head>
  <title>CentGrow Signal</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body style="font-family:sans-serif;text-align:center">
  <h2>📈 CentGrow Signal</h2>

  <p><b>Pair:</b> AUDCAD</p>
  <p id="signal">WAIT</p>

  <button onclick="buy()">BUY</button>
  <button onclick="sell()">SELL</button>
  <button onclick="wait()">WAIT</button>

  <script>
    function buy(){document.getElementById("signal").innerText="BUY";}
    function sell(){document.getElementById("signal").innerText="SELL";}
    function wait(){document.getElementById("signal").innerText="WAIT";}
  </script>
</body>
</html>
