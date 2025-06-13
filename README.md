[U<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>rem3ix — Наші послуги</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container header-flex">
            <img src="logo.jpeg" alt="rem3ix logo" class="logo">
            <h1>rem3ix</h1>
            <nav>
                <a href="#services">Послуги</a>
                <a href="#portfolio">Портфоліо</a>
                <a href="#reviews">Відгуки</a>
                <a href="#contacts">Контакти</a>
            </nav>
        </div>
    </header>

    <section id="services">
        <div class="container">
            <h2>Наші послуги</h2>
            <ul>
                <li>Ремонт квартир "під ключ"</li>
                <li>Оздоблення стін, підлоги та стелі</li>
                <li>Сантехнічні та електромонтажні роботи</li>
                <li>Дизайн інтер'єру</li>
            </ul>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Наші роботи</h2>
            <p>Тут буде галерея зображень (можна додати пізніше).</p>
        </div>
    </section>

    <section id="reviews">
        <div class="container">
            <h2>Відгуки клієнтів</h2>
            <blockquote>“Дуже задоволені роботою rem3ix. Все якісно і вчасно!”</blockquote>
            <blockquote>“Професіонали своєї справи. Рекомендуємо!”</blockquote>
        </div>
    </section>

    <section id="contacts">
        <div class="container">
            <h2>Контакти</h2>
            <p>Телефон: +38 (000) 000-00-00</p>
            <p>Email: info@rem3ix.com</p>
            <form>
                <input type="text" placeholder="Ваше ім’я" required>
                <input type="email" placeholder="Ваш Email" required>
                <textarea placeholder="Повідомлення"></textarea>
                <button type="submit">Надіслати</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 rem3ix. Всі права захищено.</p>
        </div>
    </footer>
</body>
</html>
ploading index.html…]()

![logo](https://github.com/user-attachments/assets/61585279-8826-4dc1-b372-e2e0b081a053)
[U
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f9f9f9;
    color: #333;
}

.container {
    max-width: 960px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background: #222;
    color: #fff;
    padding: 20px 0;
}

.header-flex {
    display: flex;
    align-items: center;
    gap: 20px;
}

.logo {
    height: 60px;
    width: auto;
    border-radius: 8px;
}

header h1 {
    margin: 0;
    font-size: 28px;
}

nav {
    margin-left: auto;
}

nav a {
    color: #fff;
    margin-left: 15px;
    text-decoration: none;
}

section {
    padding: 40px 0;
}

h2 {
    margin-top: 0;
}

form input, form textarea {
    display: block;
    width: 100%;
    margin-bottom: 10px;
    padding: 10px;
}

form button {
    padding: 10px 20px;
    background: #222;
    color: #fff;
    border: none;
    cursor: pointer;
}

footer {
    text-align: center;
    background: #eee;
    padding: 20px 0;
}
ploading styles.css…]()
