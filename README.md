###                                                   

<h2 align="center">
  <img src="chao.png" />
</h2>

<p align="center">
  <img src="loading.gif" />
</p>
<p align = "center">
  ______________________________________________________
</p>


<p align="center" href="streak">
  <img src="https://streak-stats.demolab.com/?user=tranghane&theme=gruvbox_duo&hide_border=true" width = "500" alt="streak"/>
</p>

<!-- index.html -->
<!DOCTYPE html>
<html>
<head>
  <title>Interactive README</title>
  <script>
    function toggleVisibility() {
      var hiddenElement = document.getElementById("hidden-text");
      if (hiddenElement.style.display === "none") {
        hiddenElement.style.display = "block";
      } else {
        hiddenElement.style.display = "none";
      }
    }
  </script>
</head>
<body>
  <h1>Interactive README</h1>
  <p>Click the button to toggle the visibility of the hidden text.</p>
  <button onclick="toggleVisibility()">Toggle Hidden Text</button>
  <p id="hidden-text" style="display: none;">This is some hidden text.</p>
</body>
</html>
