<!doctype html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Lab 4 - CSS Formatting Basics</title> 
    <link rel="stylesheet" href="lab4-styles.css"> 

 html { 

<style> 

background-color: lightgray; 

} 

body { 

  font-family: Arial; 

} 

h1 { 

  color: red; 

} 

  h1 { 

    text-align: center; 

  } 

p { 

  color: green; 

} 

p { 

  padding: 10px;  

} 

.styled-box { 

background: lightgray; 

border: 15px solid black; 
} 

</head> 
<body> 
    <header> 
        <h1>Welcome to Lab 4</h1> 
    </header> 
    <main> 
        <p>This is the first paragraph. It contains some placeholder text for styling practice.</p> 
        <p>This is the second paragraph. Feel free to add more content if you'd like.</p> 
        <ul> 
            <li>Item 1</li> 
            <li>Item 2</li> 
            <li>Item 3</li> 

              li { 

              color: green; 

              } 

        </ul> 
        <a href="https://www.tri-c.edu">Visit Cuyahoga Community College</a> 

           .no-underline:hover { 
           text-decoration: none; 
          } 
           /* Sets all links to blue for all states */ 
            a:link, a:visited, a:active { 
            color: blue; 
            } 
</style> 
    </main> 
</body> 
</html> 
