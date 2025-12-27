<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy 16th Birthday Nannu Jiya</title>
<style>
body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background: linear-gradient(120deg, #ff9a9e, #fad0c4);
  overflow: hidden;
  text-align: center;
}

.confetti {
  position: fixed;
  width: 100%;
  height: 100%;
  pointer-events: none;
}

.card {
  margin-top: 120px;
  background: white;
  padding: 30px;
  border-radius: 20px;
  display: inline-block;
  animation: pop 1.2s ease;
}

@keyframes pop {
  0% {transform: scale(0);}
  100% {transform: scale(1);}
}

h1 {
  color: #ff4081;
  font-size: 36px;
}

h2 {
  color: #333;
}

button {
  padding: 12px 25px;
  font-size: 16px;
  border: none;
  border-radius: 30px;
  background: #ff4081;
  color: white;
  cursor: pointer;
  margin-top: 20px;
}

.hidden {
  display: none;
}
</style>
</head>

<body>

<div class="card">
  <h1>🎉 Happy 16th Birthday 🎉</h1>
  <h2>NANNU JIYA 💖</h2>
  <button onclick="showWish()">Open Surprise 🎁</button>
  <p id="wish" class="hidden">
    May your 16th year be full of smiles, joy, success and happiness 🌸✨
  </p>
</div>

<script>
function showWish() {
  document.getElementById("wish").classList.remove("hidden");
}
</script>

</body>
</html>
