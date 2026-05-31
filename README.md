# Ex.06 Restaurant Website
## Name : T.Rishabh srivastav
## Reg :212224113001
# Date:



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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>KABE Restaurant</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: sans-serif; line-height: 1.6; }
    header, section, footer { padding: 20px; text-align: center; }
    nav ul { list-style: none; display: flex; justify-content: center; gap: 15px; padding: 10px 0; background: #333; }
    nav ul li a { color: white; text-decoration: none; }
    .logo { font-size: 24px; font-weight: bold; margin-bottom: 10px; }
    .btn { display: inline-block; padding: 10px 20px; background: #ff6347; color: white; text-decoration: none; border-radius: 5px; margin-top: 10px; }
    .food-items, .menu, .testimonials { display: flex; justify-content: center; flex-wrap: wrap; gap: 20px; margin-top: 20px; }
    .card { border: 1px solid #ccc; border-radius: 5px; padding: 15px; width: 250px; }
    img { max-width: 100%; border-radius: 5px; }
    footer { background: #333; color: white; padding: 10px; }
  </style>
</head>
<body>

  <header>
    <div class="logo">KABE</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#types">Types</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#testimonials">Reviews</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to KABE</h1>
    <p>Eat Right Food. Eat Healthy, Stay Happy.</p>
    <a href="#menu" class="btn">View Menu</a>
  </section>

  <section id="about">
    <h2>About KABE</h2>
    <p>We’ve been serving healthy, fresh food for over 10 years. Quality and care in every bite!</p>
  </section>

  <section id="types">
    <h2>Food Categories</h2>
    <div class="food-items">
      <div class="card">
        <img src="https://i.postimg.cc/yxThVPXk/food1.jpg" alt="Fruit">
        <h3>Fruit</h3>
      </div>
      <div class="card">
        <img src="https://i.postimg.cc/Nffm6Rkk/food2.jpg" alt="Vegetable">
        <h3>Vegetable</h3>
      </div>
      <div class="card">
        <img src="https://i.postimg.cc/76ZwsPsd/food3.jpg" alt="Grain">
        <h3>Grain</h3>
      </div>
    </div>
  </section>

  <section id="menu">
    <h2>KABE Menu</h2>
    <div class="menu">
      <div class="card">
        <img src="https://i.postimg.cc/wTLMsvSQ/food-menu1.jpg" alt="Dish 1">
        <p>Delicious dish with organic ingredients. <br><strong>₹250</strong></p>
      </div>
      <div class="card">
        <img src="https://i.postimg.cc/sgzXPzzd/food-menu2.jpg" alt="Dish 2">
        <p>Freshly prepared meal with love. <br><strong>₹250</strong></p>
      </div>
      <div class="card">
        <img src="https://i.postimg.cc/Jnxc8xQt/food-menu6.jpg" alt="Dish 3">
        <p>A balanced and healthy option. <br><strong>₹250</strong></p>
      </div>
    </div>
  </section>

  <section id="testimonials">
    <h2>Customer Reviews</h2>
    <div class="testimonials">
      <div class="card">
        <p>"KABE is my go-to place for fresh meals!"</p>
        <strong>- Ross Lee</strong>
      </div>
      <div class="card">
        <p>"Amazing food and friendly staff!"</p>
        <strong>- Amelia Watson</strong>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact KABE</h2>
    <p>Email: contact@kabe.com</p>
    <p>Phone: +91-12345-67890</p>
    <a href="#" class="btn">Send Message</a>
  </section>

  <footer>
    <p>KABE Restaurant &copy; All Rights Reserved</p>
  </footer>

</body>
</html>
```

## OUTPUT:
<img width="1770" height="770" alt="image" src="https://github.com/user-attachments/assets/227d06a7-3fb5-432e-939f-ea26be7a9ea1" />




**Terminal**
<img width="1188" height="277" alt="Screenshot 2026-05-28 201700" src="https://github.com/user-attachments/assets/00357558-3ec1-4b93-8ce1-4c1bf239b80e" />



## RESULT:
The program software company website using HTML and CSS is completed successfully.
