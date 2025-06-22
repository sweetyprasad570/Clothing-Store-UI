# Stylish Wear

Stylish Wear is a modern, responsive e-commerce front-end template designed for clothing stores. It offers a clean and intuitive user interface for showcasing various clothing collections for men, women, and kids.

## ✨ Features

* **Responsive Design:** Adapts seamlessly to different screen sizes (desktops, tablets, and mobile devices) thanks to its responsive CSS.
* **Dynamic Hero Section:** Features a full-screen background video that provides an engaging first impression.
* **Product Categories:** Dedicated sections for "All Products," "Men's Collection," "Women's Collection," and "Kids' Collection" for easy navigation.
* **Interactive Product Display:** Products are displayed with images, names, prices, and "View Details" buttons.
* **Add to Cart Functionality:** A basic shopping cart integration that allows users to add items and see a real-time count in the navigation bar (uses `localStorage`).
* **Smooth Scrolling:** Navigating between sections is smooth and user-friendly.
* **About Us & Contact Sections:** Provides essential information about the brand and ways to get in touch.
* **Clean & Modern UI:** Utilizes CSS gradients and shadows for an appealing aesthetic.
  
## 🚀 Live Demo
 👉 (Clothing Store Live) https://sweetyprasad570.github.io/Clothing-Store-UI/
## 🚀 Technologies Used

* **HTML5:** For the core structure and content of the web page.
* **CSS3:** For styling, layout, responsiveness, and visual effects (e.g., gradients, hover effects).
* **JavaScript:** For dynamic functionalities such as:
    * Implementing the "Add to Cart" logic.
    * Managing the cart item count using `localStorage` for persistence.
    * Controlling the background video playback.

## 🛒 Shopping Cart (Basic Implementation)

The `addToCart` function in the JavaScript saves items to the browser's `localStorage`. This means items added to the cart will persist even if the user closes and reopens the browser tab.

* `localStorage.getItem("cart")`: Retrieves the cart data.
* `localStorage.setItem("cart", JSON.stringify(cart))`: Saves the updated cart data.
* `updateCartCount()`: Updates the number displayed next to the cart icon.
* ## 🤝 Contributing

Feel free to fork this repository, make improvements, and submit pull requests.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE) (You should create a `LICENSE` file if you intend to use this).

---

© 2025 Stylish Wear. All rights reserved.
