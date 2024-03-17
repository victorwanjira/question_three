# question_three
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <script language="javascript">

          /*Question 3: Power of Two
      Write a program that takes an integer as input and returns true if the input is a power of two.
      Examples: 
      8=> returns true
      6=> returns false*/ 

    function divisiblity(){
      var a =prompt('Enter a number');
      var results;

      if (a%2===0){
        results='a divisible of 2';
        alert('true')
      }
      else{
        results='not a divisible of 2';
        alert('false')
      }
      document.write(results);
    }
  </script>
</head>
<body>
  <button onclick="divisiblity()">calculate</button>
  <p id="result"></p>
  
</body>
</html>
