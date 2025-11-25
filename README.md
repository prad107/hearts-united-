# hearts-united-
charity organization 
[README.md](https://github.com/user-attachments/files/23739013/README.md)
# Untitled

A Pen created on CodePen.

Original URL: [https://codepen.io/Shabirah-Newton/pen/myPyeoX](https://codepen.io/Shabirah-Newton/pen/myPyeoX).

[LICENSE.txt](https://github.com/user-attachments/files/23739017/LICENSE.txt)
The MIT License (MIT)

Copyright (c) 2025 Prada   (https://codepen.io/Shabirah-Newton/pen/myPyeoX)

Permission is hereby granted, free of charge[index.html](https://github.com/user-attachments/files/23739019/index.html)
ge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.[index.html](https://github.com/user-attachments/files/23739027/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hearts United | Charity & MoMento Collections</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f9faf9;
      color: #333;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      background-color: #2d7a36;
      color: white;
      padding: 40px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 2.4rem;
      letter-spacing: 1px;
    }

    header p {
      margin-top: 8px;
      font-size: 1.1rem;
      opacity: 0.9;
    }

    .donation-section {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 40px auto;
      gap: 20px;
      max-width: 900px;
    }

    .donation-option {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      width: 250px;
    }

    .donation-option h2 {
      color: #2d7a36;
      font-size: 1.8rem;
    }

    .donation-option p {
      font-size: 1rem;
      margin: 10px 0 20px;
    }

    .donate-btn {
      background-color: #00b964;
      color: white;
      text-decoration: none;
      padding: 12px 25px;
      border-radius: 8px;
      transition: background-color 0.3s ease;
      font-weight: bold;
      display: inline-block;
    }

    .donate-btn:hover {
      background-color: #009652;
    }

    .custom-donation {
      margin: 40px 0;
    }

    .shop-section {
      background-color: #fff;
      margin: 50px auto;
      padding: 30px 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
      max-width: 700px;
    }

    .shop-section h2 {
      color: #2d7a36;
      font-size: 1.8rem;
    }

    .shop-section p {
      font-size: 1.1rem;
      margin: 15px 0 25px;
    }

    .shop-btn {
      background-color: #222;
      color: white;
      text-decoration: none;
      padding: 12px 30px;
      border-radius: 8px;
      transition: background-color 0.3s ease;
      font-weight: bold;
      display: inline-block;
    }

    .shop-btn:hover {
      background-color: #444;
    }

    .social-section {
      margin: 40px auto;
      padding: 20px;
    }

    .social-section h3 {
      color: #2d7a36;
      font-size: 1.5rem;
    }

    .social-icons {
      margin-top: 15px;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
    }

    .social-icons a {
      text-decoration: none;
      font-size: 1rem;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      transition: opacity 0.3s ease;
      display: inline-block;
    }

    .social-icons a:hover {
      opacity: 0.85;
    }

    .facebook { background-color: #1877f2; }
    .instagram { background-color: #e1306c; }
    .whatsapp { background-color: #25d366; }
    .youtube { background-color: #ff0000; }
    .tiktok { background-color: #010101; }

    footer {
      background-color: #2d7a36;
      color: white;
      padding: 25px;
      margin-top: 50px;
      font-size: 0.95rem;
    }

    footer a {
      color: #fff;
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      .donation-section {
        flex-direction: column;
        align-items: center;
      }

      .donation-option {
        width: 80%;
      }

      .social-icons {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Hearts United Charity</h1>
    <p>In partnership with <strong>MoMento Collections (MC)</strong> — turning compassion into action.</p>
  </header>

  <main>
    <p>We aim to provide education, food, and medical care to children in vulnerable communities. Your support matters!</p>

    <div class="donation-section">
      <div class="donation-option">
        <h2>$10</h2>
        <p>Provides school supplies for one child</p>
        <a href="https://www.gofundme.com/f/your-campaign-name" target="_blank" class="donate-btn">Donate $10</a>
      </div>
      <div class="donation-option">
        <h2>$25</h2>
        <p>Feeds a child for a month</p>
        <a href="https://www.gofundme.com/f/your-campaign-name" target="_blank" class="donate-btn">Donate $25</a>
      </div>
      <div class="donation-option">
        <h2>$50</h2>
        <p>Provides medical checkup for one child</p>
        <a href="https://www.gofundme.com/f/your-campaign-name" target="_blank" class="donate-btn">Donate $50</a>
      </div>
    </div>

    <div class="custom-donation">
      <h2>Custom Donation</h2>
      <p>You can contribute any amount through our GoFundMe page:</p>
      <a href="https://www.gofundme.com/f/your-campaign-name" target="_blank" class="donate-btn">Donate Now</a>
    </div>

    <div class="shop-section">
      <h2>MoMento Collections</h2>
      <p>Shop our collection of shirts and apparel! Every purchase helps fund meals, education, and care for children in need.</p>
      <a href="https://ohr9cj-jn.myshopify.com" target="_blank" class="shop-btn">Visit Our Shopify Store</a>
    </div>

    <div class="social-section">
      <h3>Connect With Us</h3>
      <div class="social-icons">
        <a href="#" class="facebook" target="_blank">Facebook</a>
        <a href="#" class="instagram" target="_blank">Instagram</a>
        <a href="#" class="whatsapp" target="_blank">WhatsApp</a>
        <a href="#" class="youtube" target="_blank">YouTube</a>
        <a href="#" class="tiktok" target="_blank">TikTok</a>
      </div>
      <p style="margin-top:15px;">📧 Contact us at <a href="mailto:heartsunited652@gmail.com">heartsunited652@gmail.com</a></p>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 Hearts United Charity. All rights reserved.</p>
    <p>In partnership with <strong>MoMento Collections</strong> | Shopify Store: <a href="https://ohr9cj-jn.myshopify.com" target="_blank">ohr9cj-jn.myshopify.com</a></p>
  </footer>
</body>
</html>
