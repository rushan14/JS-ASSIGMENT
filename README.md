# JS-ASSIGMENT
<!-- (1)Create a simple HTML page and add a <script> tag within the page -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    document.write('With Help Of Script Tag <br><br>' )
    document.write('Ahmedabad, a city steeped in history and culture, faces the challenge of preserving its rich heritage while adapting to modern development. Protecting its iconic buildings, narrow streets, and vibrant traditions is crucial for maintaining the citys unique identity and attracting tourists, while also ensuring a better quality of life for its residents')
</script>
</html>

<!-- (2)Write JavaScript code to display an alert box with the message "Welcome toJavaScript!" when the page loads. -->
 <!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
 </head>
 <body>
    
 </body>
 <script>
    alert("WELCOME TO JAVASCRIPT")
 </script>
 </html>

 <!-- (3)Write a JavaScript program to declare variables for different data types (string,number, boolean, null, and
undefined). -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    let a = 'HELLO'
    let i = 3
    let t = true
    let val = null
    let vara = ""
    
    document.write("STRING DATA TYPE : ",a,"<br>")
    document.write("INT DATA TYPE : ",i, "<br>")
    document.write("BOOLEAN DATA TYPE : ",t ,"<br>")
    document.write("UNDEFINED DATA TYPE : ",val ,"<br>")

</script>
</html>

<!-- (4) -->
<!-- Create a JavaScript program to perform the following:
Add, subtract, multiply, and divide two numbers using arithmetic operators.
Use comparison operators to check if two numbers are equal and if onenumber is greater than the other.
Use logical operators to check if both conditions (e.g., a > 10 and b < 5)are true. -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    let a = 120
    let b = 20

    document.write("ADDITION OF A AND B IS :",(a+b) ,"<br>")
    document.write("SUBTRACTION OF A AND B IS :",(a-b) ,"<br>")
    document.write("MULTIPLICATION OF A AND B IS :",(a*b) ,"<br>")
    document.write("DIVISION OF A AND B IS :",(a/b) ,"<br>")
    document.write('*****************<br>')
    document.write('COMPARISION OPERATOR <br>')

    let c = 10 
    let d = 12

    if(c>d){
        document.write('C IS GREATER ')
    }
    else{
        document.write('D IS GREATER')
    }



</script>
</html>

<!-- (5)Write a JavaScript program to check if a number is positive, negative, or zero usingan
if-else statement. -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    let no = -5
    if(no<=0){
        document.write("NEGATIVE NUMBER")
    }else{
        document.write("POSITIVE NUMBER")
    }
</script>
</html>

<!-- (6)Create a JavaScript program using a switch statement to display the day of theweek based on the
user input (e.g., 1 for Monday, 2 for Tuesday, etc.). -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        let ch = parseInt(prompt('ENTER YOUR CHOICE'))
        switch(ch){

            case 1:document.write('MONDAY')
            break;

            case 2:document.write('TUESDAY')
            break;

            case 3:document.write('WEDNESDAY')
            break;

            case 4:document.write('THURSDAY')
            break;

            case 5:document.write('FRIDAY')
            break;

            case 6:document.write('SATURDAY')
            break;

            default:document.write('SUNDAY')
            

        }
    </script>
</body>
</html>

<!-- (7)Write a JavaScript program using a for loop to print numbers from 1 to 10.  -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    let i =1
    do {
        document.write('<br>'+i)
        i++
    } while (i<=10);
</script>
</html>

<!-- (8)Create a JavaScript
program that uses a while loop to sum all even numbers -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    
    let i = 1;
    let sum= 0

    while(i<=10){
        if(i%2===0){
            sum= sum+i
        }
        i++
    }
    document.write("Sum of even numbers from 1 to 10 : ", sum)
</script>
</html>

<!-- (9)Write a do-while loop that continues to ask the user for input until they enter a number greater than 10. -->
 <!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
 </head>
 <body>
    
 </body>
 <script>

    let a 
    do {
        a = parseInt(prompt("ENTER VALUE"));
        
    } while (i<=10)
        document.write(" NUMBER",a)
    



</script>
 </html>

 <!-- (10)Task 1: Write a function greetUser that accepts a user’s name as a parameter and displaysa greeting message
(e.g., "Hello, John!"). -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
function greetUser(john){

    document.write("HELLO JOHN")

}
greetUser()

</script>
</html>

<!-- (11)Create a JavaScript function calculateSum that takes two numbers as parameters,adds them, and returns the result. -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
function calculateSum(a,b){

       
        return a+b
}
let result = calculateSum(10,5)
document.write("ADDITION OF BOTH NUMBER WITH FUCNTION :",result)
</script>
</html>

<!-- (12)Declare an array of fruits (["apple", "banana", "cherry"]). Use JavaScript to:
Add a fruit to the end of the array.
Remove the first fruit from the array.
Log the modified array to the console. -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    let fruits = (["apple", "banana", "cherry"])
    // document.write(fruits)
    fruits.push(["mango"])
    // document.write(fruits)
    fruits.shift()
    document.write(fruits)

    


</script>
</html>

13
<!-- Create a JavaScript object car with properties brand, model, and year. UseJavaScript to:
Access and print the car’s brand and model.
Update the year property.
Add a new property color to the car object -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    let car = {
        brand:"Maruti",
        model:2015,
        year:2016
    }
    document.write("CAR BRAND : ",car.brand)
    document.write("CAR MODEL : ",car.model)
    //document.write("CAR YEAR : ",car.year)

    car.year=2018
    document.write("CAR YEAR : ",car.year)

    car.color = 'red'
    document.write("CAR COLOR IS:",car.color)

   




</script>
</html>
