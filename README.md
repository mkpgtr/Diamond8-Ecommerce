
# Live Link : https://diamond8-e-commerce-by-manish-v1.netlify.app/

# Known Bugs:

1. Some issues are also coming in  featured slider. The product slider in small devices that are not compatible with webp format can sometimes scroll unpredictably THis is happening on my Iphone6s. But on other phones that I tested, it all works fine! This may be due to Popper.js slider functionality not compatible with some devices or something like that.

2. If the some pages do not work, please use live-server to open it. This bug sometimes occurs out of nowhere. Some links appear broken or the navbar does not render correctly. Other problems may include the dropdown bars not working.

3. I have checked the project so many times and it's working fine in my laptop and mobile phone.




# (trivia/design-details) How I chose the name diamond8 :

1. Diamond8 phonetically sounds like diamond-date. What will you wear to a date that's as precious as a diamond? 
2. Elegant Clothing. Right?
3. Also, diamond is strong and so it gives this brand name a feeling of reliability and trustworthiness.
4. The crown symbol amplifies this feeling. The glowing icon also says a lot about the value of our product.
5. Diamond rhymes with Almond. Which bring us to the color-scheme that is a bit of golden-like creamish color(almond-like).
6. I guess this website was predestined to have this color scheme. I am happy that I got this scheme to vibe naturally with every other aspect of this project.


# The images and product-names and product-details

1. The images are from myntra.com and are in mostly webp format. webp format helped me to keep pictures without wasting too much space as compared to jpeg format.

# The Slider section.

1. I am using three sliders. #largeScreenSlider #mediumScreenSlider #smallScreenSlider and I am displaying them at different screen sizes.

# The Complete Project consists of :

1. Home page located in the index.html file.
2. Product pages => men.html(all-men-products), men-hoodies.html, men-pants.html, men-shirts.html
                  => women.html(all-women-products),women-dresses.html,women-pants.html
                  => kids.html
                  => all-products.html

3. Other pages => cart-page.html, login-page.html, contact.html


#  Comments

1. I have used as much comments as possible to keep my thought process transparent and also to establish the fact that this project is the result of my original work.

# lorem ipsum and random names

1. The products have been populated with random ipsum texts and item name/product name just as a placeholder. Some real names are coming from the products.js where the array of objects live. In there, I have given some products their real names.



            

# Folder structure:

1. I have put all the pages in the pages folder. The rest is self-explanatory.
2.  I have maintained a neat folder structure to let the project evaluator navigate intuitively around my project.

# The glowing css effect 

1. is situated in the styles.css file inside the styles folder. Please look at the .name-n-slogan-container class to see the logic of the glowing css. Along with the glowing css, I have added hover effects to all buttons.

# The color scheme 

1. is something with occured randomly to me about two days after I started building this project. I am happy with this color scheme. Choosing a color scheme and making it consistent across pages is hard for a beginner like me.

# Dynamic Header and Footer

1. The header and footer are dynamically generated from the .nav-populator file. the nav-populator file is located in multiple folders in this project according to the files which need it.

# The product page populates all the product values to 350 dollars as it felt quite redundant to do that over and over again.

1. The hoodies-page.html has a script products.js(located inside /pages/product-categories/). this file dynamically populates some of the hoodie images. this data is stored as an array of objects in the products.js

 
# Cart Page 

1. Is not dynamic. But the input buttons increase and decrease the input box value upto maximum of 10.
2. The summary box has sticky top position property which makes it float along with the scroll-bar.
3. I have kept three items just to showcase that my code is component based and is also reusable.


# navbar search design

1. The unique navbar search design which was given in the assignment was completed by me. It used border radius property to achieve this. But before that, I wrapped the input box and the search button into one div and made it a flex-container.

# The hero section


# All pages are responsive

1. Built with Bootstrap.

# Lots of CSS

1. I have written lots of CSS for this and not each thing can be described in the Readme.md.
2. I have also added a sale tag in the kids section. I have written it such that it is re-usable. Also, a lot of frontend libraries like React use conditional styling.
3. Keeping in view the long-term vision and to make code maintainable and reusbale, I have kept the sale tag and it's styling quite minimal and to the point.

# Populating Products with a for loop.

1. I am inspired by the long-ranging benefits of understanding loops and how they work. I used one loop in this project and it's quite fascinating to see such things in action. I have done this in the products.js.
2. Used template literals to inject html.


# Login Page

1. email : admin@admin.com 
    password : password
2. If correct, then A green alert will tell the login was succesful.
3. If incorrect, a red alert will tell the user to provide the correct Credentials.
