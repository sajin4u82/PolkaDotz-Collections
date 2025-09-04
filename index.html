<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Jewelry Collection</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0; padding: 0;
    background: #f7f3f0;
  }
  header {
    background: #8b4513;
    color: white;
    padding: 1rem;
    text-align: center;
  }
  nav {
    margin: 10px 0;
    text-align: center;
  }
  nav a {
    margin: 0 15px;
    color: #8b4513;
    text-decoration: none;
    font-weight: bold;
  }
  nav a:hover {
    text-decoration: underline;
  }
  .landing {
    padding: 2rem;
    text-align: center;
    background: #fff0de;
  }
  .landing h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  .landing p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
  }
  .btn-collections {
    background: #8b4513;
    color: white;
    padding: 1rem 2rem;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1rem;
  }
  .btn-collections:hover {
    background: #a05523;
  }

  /* Collections page */
  .products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 2rem;
    max-width: 900px;
    margin: auto;
  }
  .product-card {
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 8px #d4b27e80;
    width: 200px;
    padding: 1rem;
    text-align: center;
  }
  .product-card img {
    width: 100%;
    border-radius: 8px;
    height: 180px;
    object-fit: cover;
  }
  .product-name {
    font-weight: bold;
    margin: 10px 0 5px;
  }
  .product-price {
    color: #a67843;
    margin-bottom: 10px;
  }
  .btn-addcart {
    background: #8b4513;
    color: white;
    border: none;
    padding: 8px 12px;
    border-radius: 4px;
    cursor: pointer;
  }
  .btn-addcart:hover {
    background: #a05523;
  }

  /* Cart section */
  #cart {
    max-width: 900px;
    margin: 2rem auto;
    background: #fff8e1;
    padding: 1rem;
    border-radius: 8px;
  }
  #cart h2 {
    color: #8b4513;
  }
  #cart-items {
    margin: 1rem 0;
  }
  .cart-item {
    display: flex;
    justify-content: space-between;
    margin-bottom: 0.7rem;
  }
  .remove-item {
    cursor: pointer;
    color: red;
    font-weight: bold;
  }
  #whatsapp-order {
    background: #25d366;
    color: white;
    border: none;
    padding: 1rem 1.5rem;
    border-radius: 6px;
    cursor: pointer;
    font-weight: bold;
    font-size: 1.1rem;
  }
  #whatsapp-order:disabled {
    background: #8fd5ac;
    cursor: not-allowed;
  }
</style>
</head>
<body>

<header>
  <h1>Elegant Jewelry</h1>
</header>

<nav>
  <a href="#" id="nav-home">Home</a>
  <a href="#" id="nav-collection">Collections</a>
</nav>

<main>
  <!-- Landing page -->
  <section id="landing-page" class="landing">
    <h1>Welcome to Elegant Jewelry</h1>
    <p>Discover our exclusive collection of handcrafted jewelry made with love and elegance.</p>
    <button class="btn-collections" id="go-to-collections">Explore Collections</button>
  </section>

  <!-- Collections page -->
  <section id="collections-page" style="display:none;">

    <div class="products" id="product-list">
      <!-- Products will be added here dynamically -->
    </div>

    <div id="cart">
      <h2>Your Cart</h2>
      <div id="cart-items">
        <p>Your cart is empty.</p>
      </div>
      <button id="whatsapp-order" disabled>Order via WhatsApp</button>
    </div>

  </section>
</main>

<script>
  // Sample product data
  const products = [
    { id: 1, name: "Gold Plated Necklace", price: 1200, image: "https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=400&q=80" },
    { id: 2, name: "Silver Stud Earrings", price: 450, image: "https://images.unsplash.com/photo-1512436991641-6745cdb1723f?auto=format&fit=crop&w=400&q=80" },
    { id: 3, name: "Pearl Bracelet", price: 780, image: "https://images.unsplash.com/photo-1532314831367-39a6de189565?auto=format&fit=crop&w=400&q=80" },
    { id: 4, name: "Diamond Ring", price: 3500, image: "https://images.unsplash.com/photo-1546435770-a3e426bf472b?auto=format&fit=crop&w=400&q=80" },
  ];

  const cart = [];

  // Elements
  const landingPage = document.getElementById("landing-page");
  const collectionsPage = document.getElementById("collections-page");
  const productList = document.getElementById("product-list");
  const cartItemsContainer = document.getElementById("cart-items");
  const whatsappOrderButton = document.getElementById("whatsapp-order");

  // Navigation buttons
  document.getElementById("nav-home").addEventListener("click", () => {
    showLandingPage();
  });

  document.getElementById("nav-collection").addEventListener("click", () => {
    showCollectionsPage();
  });

  document.getElementById("go-to-collections").addEventListener("click", () => {
    showCollectionsPage();
  });

  function showLandingPage() {
    landingPage.style.display = "block";
    collectionsPage.style.display = "none";
  }

  function showCollectionsPage() {
    landingPage.style.display = "none";
    collectionsPage.style.display = "block";
  }

  // Render products in collections
  function renderProducts() {
    productList.innerHTML = "";
    products.forEach(product => {
      const div = document.createElement("div");
      div.className = "product-card";
      div.innerHTML = `
        <img src="${product.image}" alt="${product.name}" />
        <div class="product-name">${product.name}</div>
        <div class="product-price">₹${product.price.toLocaleString()}</div>
        <button class="btn-addcart" data-id="${product.id}">Add to Cart</button>
      `;
      productList.appendChild(div);
    });

    // Add event listeners for Add to Cart buttons
    document.querySelectorAll(".btn-addcart").forEach(button => {
      button.addEventListener("click", () => {
        const productId = parseInt(button.getAttribute("data-id"));
        addToCart(productId);
      });
    });
  }

  // Add item to cart
  function addToCart(productId) {
    const foundIndex = cart.findIndex(item => item.id === productId);
    if (foundIndex > -1) {
      cart[foundIndex].quantity += 1;
    } else {
      const product = products.find(p => p.id === productId);
      cart.push({...product, quantity: 1});
    }
    renderCart();
  }

  // Remove item from cart
  function removeFromCart(productId) {
    const index = cart.findIndex(item => item.id === productId);
    if (index > -1) {
      if (cart[index].quantity > 1) {
        cart[index].quantity -= 1;
      } else {
        cart.splice(index, 1);
      }
    }
    renderCart();
  }

  // Render cart items
  function renderCart() {
    if (cart.length === 0) {
      cartItemsContainer.innerHTML = "<p>Your cart is empty.</p>";
      whatsappOrderButton.disabled = true;
      return;
    }

    whatsappOrderButton.disabled = false;

    cartItemsContainer.innerHTML = "";
    cart.forEach(item => {
      const div = document.createElement("div");
      div.className = "cart-item";
      div.innerHTML = `
        <span>${item.name} × ${item.quantity} (₹${(item.price * item.quantity).toLocaleString()})</span>
        <span class="remove-item" data-id="${item.id}">&times;</span>
      `;
      cartItemsContainer.appendChild(div);
    });

    // Add event listeners to remove buttons
    document.querySelectorAll(".remove-item").forEach(btn => {
      btn.addEventListener("click", () => {
        const id = parseInt(btn.getAttribute("data-id"));
        removeFromCart(id);
      });
    });
  }

  // WhatsApp order button click
  whatsappOrderButton.addEventListener("click", () => {
    if (cart.length === 0) return;

    // Compose message
    let message = "Hello, I would like to order the following jewelry:%0A";
    cart.forEach(item => {
      message += `- ${item.name} × ${item.quantity} (₹${item.price * item.quantity})%0A`;
    });
    const total = cart.reduce((sum, item) => sum + item.price * item.quantity, 0);
    message += `Total Price: ₹${total}%0AThank you!`;

    // Your WhatsApp number in international format without + or leading zeros
    const whatsappNumber = "919495988327";

    // Open WhatsApp with message
    const whatsappUrl = `https://wa.me/${whatsappNumber}?text=${message}`;
    window.open(whatsappUrl, "_blank");
  });

  // Initialize the site by showing landing page and rendering products
  showLandingPage();
  renderProducts();
</script>

</body>
</html>
