# tutui.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
  <title>クイズ筒井</title>

</head>  

<body>
  <h1>クイズ筒井</h1>

  <div class="container">
    
    <div class="jumbotron mt-5">
      <div class="d-flex justify-content-center">
        <div id="js-question" class="alert alert-primary" role="alert">
          A simple primary alert—check it out!
        </div>
      </div>
      
      <div id="js-items" class="d-flex justify-content-center">
        <div class="m-2">
          <button type="button" id="js-btn-1" class="btn btn-primary">Primary</button>
        </div>
        <div class="m-2">
          <button type="button" id="js-btn-2" class="btn btn-primary">Primary</button>
        </div>
        <div class="m-2">
          <button type="button" id="js-btn-3" class="btn btn-primary">Primary</button>
        </div>
        <div class="m-2">
          <button type="button" id="js-btn-4" class="btn btn-primary">Primary</button>
        </div>
      </div>
    </div>
  </div>
  
  <script src="app.js"></script>
</body>

</html>
