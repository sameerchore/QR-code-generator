# QR Code Generator

This is a simple web app that generates a QR Code from user input (text or URL) using a free QR code API.

---

## 🧠 How It Works

1. User enters text or a link in the input box.
2. On clicking **"Generate QR Code"**:
   - The input by user store in inputText.src that sends to img tag.
   - The `imgBox` container becomes visible by adding the `.show-img` class using JavaScript.
   - After you click the "Generate QR Code" button, JavaScript adds the class: imgBox.classList.add("show-img");(in js code)
   - After adding class we can use class in css


---

## 📌 Key Concepts

### 1. 📷 `.src` Property in JavaScript

```js
qetImg.src = "https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=" + inputText.value;

