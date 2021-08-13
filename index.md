<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="calculator.css">
    <script src="calculator.js"></script>
</head>
<body>
  
    <div class="container" id="app">
      <h2><marquee behavior="alternate">
      <font color="White">Calculator Created by Pradeep Kumar Gupta</font></marquee>
      </h2>
     <div class="box">
      <div class="display"><input type="text" readonly size="20" id="d"></div>
      <div class="keys">
       <p>
        <input type="button" class="button" value="mrc" onclick='c("Calculator Created...")'>
        <input type="button" class="button" value="m-" onclick='c("................by................")'>
        <input type="button" class="button" value="m+" onclick='c("Pradeep Kumar Gupta")'>
        <input type="button" class="button" value="/" onclick='v("/")'>
      </p>
      <p>
       <input type="button" class="button" value="7" onclick='v("7")'>
       <input type="button" class="button" value="8" onclick='v("8")'>
       <input type="button" class="button" value="9" onclick='v("9")'>
       <input type="button" class="button" value="*" onclick='v("*")'>
     </p>
     <p>
       <input type="button" class="button" value="4" onclick='v("4")'>
       <input type="button" class="button" value="5" onclick='v("5")'>
       <input type="button" class="button" value="6" onclick='v("6")'>
       <input type="button" class="button" value="-" onclick='v("-")'>
     </p>
     <p>
       <input type="button" class="button" value="1" onclick='v("1")'>
       <input type="button" class="button" value="2" onclick='v("2")'>
       <input type="button" class="button" value="3" onclick='v("3")'>
       <input type="button" class="button" value="+" onclick='v("+")'>
     </p>
     <p>
       <input type="button" class="button" value="0" onclick='v("0")'>
       <input type="button" class="button" value="." onclick='v(".")'>
       <input type="button" class="button" value="C" onclick='c("")'>
       <input type="button" class="button" value="=" onclick='e()'>
     </p>
    </div>
   </div>
  </div>
</body>
</html>
