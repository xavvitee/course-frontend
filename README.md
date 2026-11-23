# Section 2: HTML5 - Text Formatting in HTML 
## Coding Exercise 1: Text Formatting Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<h1>My First Webpage</h1>
    <p>This is a <strong>bold</strong> and <em>italic</em> text in HTML.</p>
    <ul>
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
    </ul>
    <blockquote>
        "The only limit to our realization of tomorrow will be our doubts of today." -Franklin D. Roosevelt
    </blockquote>    
</body>
</html>
```

# Section 3: HTML5-HTML Essential
## Coding Exercise 2: HTML Essentials Coding Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<h1>Links Example</h1>
    <p>Below are link examples</p>
    <ul>
        <li><a href="https://www.example.com">Absolute URL</a></li>
        <li><a href="relative_page.html">Relative URL</a></li>
        <li><a href="#">Link to Top of Page</a></li>
    </ul>
</body>
</html>
```

# Section 4: HTML5- Images in HTML 
## Coding Exercise 3: Images Coding Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<h1>Welcome to My Website</h1>
    <p>This is a simple example of HTML content.</p>
    <figure>
        <img src="https://primeinspire.com/wp-content/uploads/2023/09/Albert-Einstein.jpg" alt="Albert Einstein">
        <figcaption>Albert Einstein</figcaption>
    </figure>
</body>
</html>
```

# Section 5: HTML5- Multimedia in HTML 
## Coding Exercise 4: Multimedia Coding Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<h1>Welcome to My Website</h1>
    <p>This is a simple example of HTML content.</p>
    <video width="640" height="360" controls>
        <source src="https://primeinspire.com/wp-content/uploads/2023/09/success.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</body>
</html>
```

# Section 6: HTML5- Content in HTML 
## Coding Exercise 5: Content in HTML Coding Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<div>
        <header>
            <nav>Nav</nav>
        </header>
        <main>
            <article>
                <section>Content of the site</section>
            </article>
            <aside>Sidebar</aside>
        </main>
        <footer>Footer of the site</footer>
    </div>
</body>
</html>
```

# Section 7: HTML5- Form Elements in HTML
## Coding Exercise 6: Coding Exercise to Create a Simple Login Page
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        label{
            display: block;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
<form action="" method="post">
        <label for="u_name">Username:
            <input type="text" id="u_name" placeholder="Username" required>
        </label>
        <label for="u_pass">Password:
            <input type="password" id="u_pass" placeholder="Password" required>
        </label>
        <input type="submit" value="Sign in">
    </form>
</body>
</html>
```

# Section 8: HTML5- Tables in HTML
## Coding Exercise 7: Tables in HTML Coding Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table {
            border-collapse: collapse; /* This ensures that adjacent cell borders merge into one */
        }

        table, th, td {
            border: 1px solid black; /* Add a 1px solid black border to the table, table headers, and table data cells */
            padding: 8px; /* Add some padding to the cells for spacing */
        }
    </style>
</head>
<body>
<table>
        <tr>
            <th>Student ID</th>
            <th>Name</th>
            <th>Age</th>
            <th>Grade</th>
        </tr>
        <tr>
            <td>001</td>
            <td>John Doe</td>
            <td>20</td>
            <td>A</td>
        </tr>
        <tr>
            <td>002</td>
            <td>Jane Smith</td>
            <td>22</td>
            <td>B</td>
        </tr>
        <tr>
            <td>003</td>
            <td>Bob Johnson</td>
            <td>21</td>
            <td>C</td>
        </tr>
    </table>
</body>
</html>
```

# Section 9: CSS3- Getting started with CSS
## Coding Exercise 8: CSS Placement and Syntax Coding Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            color: red;
        }
    </style>
</head>
<body>

<h1>CSS is Awesome</h1>
<p>And you can't deny it!</p>

</body>
</html>
```

# Section 10: CSS3- Essentials
## Coding Exercise 9: CSS Selectors and Pseudo Coding Exercise

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h3 {
            font-family: sans-serif;
        }
        h3 strong {
            color: goldenrod;
        }
        h3 strong:hover {
            color: red;
        }
    </style>
</head>
<body>

<h3>You need to change color on <strong>Hover</strong></h3>

</body>
</html>
```
# Section 11: CSS3- Understanding Box Model in CSS
## Coding Exercise 10: Box Model Coding Exercise
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        section {
            display: inline-block;
            background-color: crimson;
            padding: 25px;
            color: white;
            font-family: monospace;
        }
        section em {
            color: yellow;
        }
        section a {
            display: inline-block;
            color: white;
            background-color: black;
            padding: 10px;
        }
        section a:hover {
            background-color: white;
            color: black;
        }
    </style>
</head>
<body>

<section>
    <h3>Welcome to <em>Box Model</em></h3>
    <p>Box Model is what make the web style stand out</p>
    <a href="#">It's True</a>
</section>

</body>
</html>
```
# Section 12: CSS3- Typography in CSS
## Coding Exercise 11: Importing Custom Fonts Coding Exercise
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fuggles&display=swap" rel="stylesheet">
    <style>
        h3 {
            font-family: 'Fuggles', cursive;
            font-size: 60px;
            margin: 5px 0px;
        }
    </style>
</head>
<body>

<section>
    <h3>This is a Fancy Font</h3>
</section>

</body>
</html>
```
# Section 13: CSS3- Layouts in CSS
## Coding Exercise 12: Layout Coding Exercise
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box1, .box2, .box3 {
            width: 200px;
            height: 200px;
            position: absolute;
        }
        .box1 {
            background-color: red;
            left: 20px;
            top: 20px;
        }
        .box2 {
            background-color: green;
            left: 40px;
            top: 40px;
        }
        .box3 {
            background-color: blue;
            left: 60px;
            top: 60px;
        }
    </style>
</head>
<body>
    
<div class="box1"></div>
<div class="box2"></div>
<div class="box3"></div>

</body>
</html>
```
# Section 14: CSS3- Flexbox and Grid in CSS
## Coding Exercise 13: Flexbox Coding Exercise
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .container {
            width: 500px;
            height: 500px;
            display: flex;
            background-color: teal;
            margin: auto;
            justify-content: center;
            align-items: center;
        }
        .box {
            width: 100px;
            height: 100px;
            background-color: aqua;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="box"></div>
</div>
    
</body>
</html>
```

## Section 15: CSS3- Advanced CSS Selections
```
Coding Exercise 14: Advanced CSS Selectors Coding Exercise
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        p:first-of-type {
            color: brown;
            font-style: italic;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>This is a demo heading</h1>
    <p>1st Paragraph</p>
    <p>2nd Paragraph</p>
    <p>3rd Paragraph</p>
</div>
    
</body>
</html>
```

## Section 20: Modern JavaScript - Variables, Scopes, and More
```
Coding Exercise 15: Check Variable Scope Exercise
let x = "red";
console.log(x);

function change_to_blue() {
    let inside_x = "blue";
    console.log("Inside function data: " + inside_x);
}

change_to_blue();
console.log(x);
```

## Coding Exercise 16: Data Types Coding Exercise
```
// String
let string_demo = "This is a string";
console.log('String: ', typeof string_demo);

// Number
let number_demo = 25;
console.log('Number: ', typeof number_demo);

// Floats
let floats_demo = 25.5;
console.log('Float: ', typeof floats_demo);

// Booleans
let booleans_demo = true;
console.log('Boolean: ', typeof booleans_demo);

// Null
let null_demo = null;
console.log('Null: ', typeof null_demo);

// Undefined
let undefined_demo = undefined;
console.log('Undefined with value: ', typeof undefined_demo);

let undefined_demo2;
console.log('Undefined without value', typeof undefined_demo2);

// Objects
const objects_demo = {
    width: 250,
    height: 250,
    color: "red"
}
console.log('Object: ', typeof objects_demo);

// Arrays
const array_demo = ['Apple', 'Mango', 'Orange'];
console.log('Array: ', typeof array_demo);

// Arrays
const array_demo = ['Apple', 'Mango', 'Orange'];
console.log('Array: ', typeof array_demo);
```
