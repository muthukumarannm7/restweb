# Ex.06 Restaurant Website
## Date:25-12-2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flavour Fix</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Flavour Fix</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="home">      
        <h1>Welcome to Flavour Fix</h1>
        <p>Where every dish tells a story</p>
    </section>
     <section id="story"class="story">
            <h2>Our Story</h2>
            <p>
               Flavour Fix is not just a place to eat; it is a conceptual experience built on the philosophy that mastery of flavor's foundation (Salt) must precede the thrill of its extreme sensation (Spice). Chef Elias Thorne’s goal is to prove that spice shouldn't mask poor seasoning but should elevate perfect seasoning.
            </p>
        </section>
    <footer>
        <p>&copy; 2025 Flavour Fix. All Rights Reserved.</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
    <h1>The Flavour Fix</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="menu" class="story">
        <h2>Today's Special</h2>
        <div class="menu">
            <div class="items">
                <h3>Hamburger</h3>
                <img src="https://www.allrecipes.com/thmb/UsNtGp9OgIsKw6cPqGQ-CxLmnTE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/AR-72657-best-hamburger-ever-ddmfs-4x3-hero-878e801ab30445988d007461782b3c25.jpg" alt="Hamburger" align="center">
                <p>a perfect handheld harmony of savory beef, crisp toppings, and soft bread, elevated by a secret, simple sauce.</p>
            </div>
            <div class="items">
                <h3>Grilled Chicken Salad</h3>
                <img src="https://assets.epicurious.com/photos/64a845e67799ee8651e4fb8f/16:9/w_6179,h_3476,c_limit/AshaGrilledChickenSalad_RECIPE_070523_56498.jpg" alt="Grilled Chicken Salad" align="center">
                <p>Fresh mixed greens topped with grilled chicken, cherry tomatoes, cucumbers, and a light vinaigrette.</p>
            </div>
            <div class="items">
                <h3>Pepperoni Pizza</h3>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQoYWUM5Lpw8wwHe5aK6e9R4o1OOwI4XRsPLg&s" alt="Pepperoni Pizza" align="center">
                <p>Classic pizza topped with pepperoni slices, mozzarella cheese, and a rich tomato sauce.</p>
            </div>
            <div class="items">
                <h3>Hot Dog</h3>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQOXXv0NFZAmW6hylPctsNPA6JFk2RfsjEM3A&s" alt="Hot dog" align="center">
                <p>A grilled sausage served in a soft bun, topped with mustard, ketchup, onions, and relish.</p>
            </div>
            <div class="items">
                <h3>Tacos</h3>
                <img src="https://danosseasoning.com/wp-content/uploads/2022/03/Beef-Tacos-1024x767.jpg" alt="Tacos" align="center">
                <p>Soft corn tortillas filled with seasoned meat, lettuce, cheese, and salsa.</p>
            </div>
            <div class="items">
                <h3>Sandwich</h3>
                <img src="https://recipes.timesofindia.com/thumb/83740315.cms?width=1200&height=900" alt="Sandwich" align="center">
                <p>Layers of deli meats, cheese, lettuce, and tomato between two slices of fresh bread.</p>
            </div>
            <div class="items">
                <h3>French Fries</h3>
                <img src="https://images.themodernproper.com/production/posts/2022/Homemade-French-Fries_8.jpg?w=1200&h=1200&q=60&fm=jpg&fit=crop&dm=1662474181&s=15046582e76b761a200998df2dcad0fd" alt="French Fries" align="center">
                <p>Crispy golden fries, perfectly salted and served with ketchup or your favorite dipping sauce.</p>
            </div>
            <div class="items">
                <h3>Fried Chicken</h3>
                <img src="https://vaya.in/recipes/wp-content/uploads/2018/05/Fried-Chicken.jpg" alt="Fried Chicken" align="center">
                <p>Juicy chicken pieces coated in a crispy, seasoned batter and deep-fried to perfection.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 The Flavour Fix. All Rights Reserved.</p>
    </footer>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - The Flavour Fix</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
       <h1>The Flavour Fix</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>Staff Members</h2>
        <div class="menu">
            <div class="staff">
                <img src="https://images.stockcake.com/public/e/c/9/ec99397d-f907-4b71-b645-479318f7c71e_large/chef-serving-food-stockcake.jpg" alt="John Doe - Head Chef" style="width:200px;height:auto;">
                <h3>Doe</h3>
            </div>
            <div class="staff">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTaVeKEbOxwd8ET5zBL2R1Uao5kR5i5xNAJTQ&s" alt="Jane Smith - Pastry Chef" style="width:200px;height:auto;">
                <h3>Smith</h3>
            </div>
            <div class="staff">
                <img src="https://i.pinimg.com/474x/d2/35/47/d2354797cfb995122e8bf0248cb1fd76.jpg" alt="Mike Johnson - Restaurant Manager" style="width:200px;height:auto;">
                <h3>Johnson</h3>
            </div>
            <div class="staff">
                 <img src="https://images.stockcake.com/public/c/1/c/c1c4ed49-3fdc-4ce5-a253-04bf41089b15_large/happy-professional-chef-stockcake.jpg" alt="Emily Davis - Sommelier" style="width:200px;height:auto;">           
                 <h3>Davis</h3>
                </div>
            <div class="staff">
               <img src="https://images.stockcake.com/public/9/2/e/92e9edad-b917-4b51-826e-fab97dbd714b_large/smiling-female-chef-stockcake.jpg" alt="Sarah Brown - Marketing Specialist" style="width:200px;height:auto;">
                 <h3>Brown</h3>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 The Flavour Fix. All Rights Reserved.</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
     <header>
        <h1>The Flavour Fix</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="contact" class="story">
             <h2>Visit Us or Make a Reservation</h2>
            <p>We are located at 123 Foodie Lane,Flavour City.</p>
            <p><strong>Phone:</strong>985674587</p>
            <p><strong>Email:</strong> reservations@flavourfix.com</p>
            <br>
            <p><strong>Hours:</strong></p>
            <p>Monday - Thursday: 5:00 PM - 10:00 PM</p>
            <p>Friday - Sunday: 4:00 PM - 11:00 PM</p>
    </section>
    <footer>
        <p>&copy; 2025 Flavour Fix. All Rights Reserved.</p>
    </footer>
</body>
</html>

style.css

body{
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #000000;
        }
        header{
            background-color: #000000;
            color: #d60000;
            font-family: 'brush script mt', cursive;
            font-size: 1.2em;
            padding: 0.1em 2em;
            display: flex;
            position: sticky;
            justify-content: space-between;
            align-items: center;     
        }
        nav ul{
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 2rem;
        }
        nav a{
            color: #d60000;
            text-decoration: none;
            font-size: 1.5em;
        }
        .home{
            background: url('https://images.unsplash.com/photo-1558030137-d464dd688b00?q=80&w=1331&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D') center/cover no-repeat;
            height: 100vh;
            padding: 0.1em 0em;
            text-align: center;
            align-content: center;
            color:#ffffff;
            font-size: 2em;
            font-family:'Playfair Display', serif;
            font-style:italic;
            text-shadow: 2px 2px 6px #000;
        }
        section{
            text-align: center;
            font-size: 1.5em;
            font-family: 'Playfair Display', serif;
            font-style: bold;
            padding: 2em;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 2em;
        }
        .items {
            background-color: #fb8818;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.815);
            padding: 1em;
            width: 250px;
        }
        .items img{
            width: 100%;
            border-radius: 10px;
        }
        .story{
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
        }
        .staff{
            background-color: #9f9e9e;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.815);
            padding: 1em;
            width: 250px;
        }
        footer {
        background-color: #000000;
        color: #d60000;
        text-align: center;
        padding: 0.5em;
        }
```


## OUTPUT:
home.html
![alt text](<Screenshot 2025-12-25 134637.png>)

menu.html
![alt text](<Screenshot 2025-12-25 134718-1.png>)

about.html
![alt text](<Screenshot 2025-12-25 134735.png>)

contact.html
![alt text](<Screenshot 2025-12-25 134746.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
