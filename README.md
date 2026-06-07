<!DOCTYPE html>
<html lang="gu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>મહાવીર પપૅકોર્ન - Mahavir Popcorn</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">🍿 મહાવીર પપૅકોર્ન</div>
            <ul class="nav-menu">
                <li><a href="#home" onclick="changeLanguage('gu')">ગુજરાતી</a></li>
                <li><a href="#home" onclick="changeLanguage('en')">English</a></li>
                <li><a href="#products">Products / પણ્યો</a></li>
                <li><a href="#about">About / વિશે</a></li>
                <li><a href="#contact">Contact / સંપર્ક</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1 id="hero-title">મહાવીર પપૅકોર્ન</h1>
            <p id="hero-subtitle">સૌથી સ્વાદિષ્ટ પપૅકોર્ન</p>
            <a href="#products" class="btn btn-primary" id="btn-shop">પણ્યો જુઓ</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <h2 id="products-title">આપણી પણ્યો</h2>
        <div class="products-grid">
            <!-- Salt Popcorn -->
            <div class="product-card">
                <div class="product-image">🍿</div>
                <h3 id="salt-name">મીઠું પપૅકોર્ન</h3>
                <div class="sizes">
                    <div class="size-item">
                        <span id="size-small">નાનું (50g)</span>
                        <span class="price">₹10</span>
                    </div>
                    <div class="size-item">
                        <span id="size-medium">મધ્યમ (100g)</span>
                        <span class="price">₹20</span>
                    </div>
                    <div class="size-item">
                        <span id="size-large">મોટું (200g)</span>
                        <span class="price">₹30</span>
                    </div>
                </div>
                <button class="btn btn-secondary" id="btn-order">ઓર્ડર કરો</button>
            </div>

            <!-- Spicy Popcorn -->
            <div class="product-card">
                <div class="product-image">🌶️🍿</div>
                <h3 id="spicy-name">મસાલેદાર પપૅકોર્ન</h3>
                <div class="sizes">
                    <div class="size-item">
                        <span id="size-small-2">નાનું (50g)</span>
                        <span class="price">₹10</span>
                    </div>
                    <div class="size-item">
                        <span id="size-medium-2">મધ્યમ (100g)</span>
                        <span class="price">₹20</span>
                    </div>
                    <div class="size-item">
                        <span id="size-large-2">મોટું (200g)</span>
                        <span class="price">₹30</span>
                    </div>
                </div>
                <button class="btn btn-secondary" id="btn-order-2">ઓર્ડર કરો</button>
            </div>

            <!-- Cheese Popcorn -->
            <div class="product-card">
                <div class="product-image">🧀🍿</div>
                <h3 id="cheese-name">ચીઝ પપૅકોર્ન</h3>
                <div class="sizes">
                    <div class="size-item">
                        <span id="size-small-3">નાનું (50g)</span>
                        <span class="price">₹10</span>
                    </div>
                    <div class="size-item">
                        <span id="size-medium-3">મધ્યમ (100g)</span>
                        <span class="price">₹20</span>
                    </div>
                    <div class="size-item">
                        <span id="size-large-3">મોટું (200g)</span>
                        <span class="price">₹30</span>
                    </div>
                </div>
                <button class="btn btn-secondary" id="btn-order-3">ઓર્ડર કરો</button>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2 id="about-title">આપણા વિશે</h2>
        <div class="about-content">
            <p id="about-text">
                મહાવીર પપૅકોર્ન એક પરિવારનો ધંધો છે જે સૌથી સ્વાદિષ્ટ અને તાજું પપૅકોર્ન આપે છે. 
                આપણે માત્ર શ્રેષ્ઠ ગુણવત્તાની સામગ્રી ઉપયોગ કરીએ છીએ.
            </p>
            <div class="owners">
                <div class="owner">
                    <h4>નિતિન ભાઈ</h4>
                    <p id="owner-phone">📱 9714223347</p>
                </div>
                <div class="owner">
                    <h4>પીયુષ ભાઈ</h4>
                    <p id="owner-phone-2">📱 1478965320</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2 id="contact-title">સંપર્ક કરો</h2>
        <div class="contact-info">
            <div class="contact-item">
                <span id="contact-address">📍 સરનામું:</span>
                <p>110, Chabutra Same Main Bajar, Panvad, Gujarat 391168</p>
            </div>
            <div class="contact-item">
                <span id="contact-phone">📞 ફોન:</span>
                <p>9714223347 / 1478965320</p>
            </div>
            <div class="contact-item">
                <span id="contact-email">📧 ઈમેલ:</span>
                <p><a href="mailto:rathvapiyushk11@gmail.com">rathvapiyushk11@gmail.com</a></p>
            </div>
        </div>
        <form class="contact-form" onsubmit="handleSubmit(event)">
            <input type="text" id="form-name" placeholder="નામ / Name" required>
            <input type="email" id="form-email" placeholder="ઈમેલ / Email" required>
            <input type="tel" id="form-phone" placeholder="ફોન / Phone" required>
            <textarea id="form-message" placeholder="સંદેશ / Message" rows="5" required></textarea>
            <button type="submit" class="btn btn-primary" id="btn-submit">મોકલો / Submit</button>
        </form>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p id="footer-text">&copy; 2025 મહાવીર પપૅકોર્ન. તમામ અધિકાર સુરક્ષિત છે.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
