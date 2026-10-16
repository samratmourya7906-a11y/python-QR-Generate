# python-QR-Generate
QR Code Generator Using Python

📌 Project Overview

The QR Code Generator is a Python-based project that creates QR codes for text, URLs, website links, and other information. It provides a simple and efficient way to convert data into a scannable QR code.

🎯 Project Objectives

- Generate QR codes from text and URLs.
- Convert information into a scannable QR code image.
- Understand the practical implementation of Python libraries.
- Develop basic Python programming and project-building skills.

🛠️ Technologies Used

- Programming Language: Python
- Library: qrcode
- Image Processing: Pillow (PIL)

⚙️ Features

- Generate QR codes quickly and easily.
- Support text and website URLs.
- Save generated QR codes as image files.
- Simple and beginner-friendly implementation.

📥 Installation

Install the required Python libraries using the following command:

pip install qrcode[pil]

▶️ How to Run

1. Install Python on your system.
2. Install the required library.
3. Open the project in VS Code or another Python editor.
4. Run the Python program.
5. Enter the required text or URL, if prompted.
6. Scan the generated QR code using a smartphone.

💻 Example Code

import qrcode

data = "https://www.google.com"

qr = qrcode.make(data)
qr.save("qrcode.png")

print("QR Code generated successfully!")

📂 Project Output

The program generates a QR code image named "qrcode.png", which can be scanned to access the encoded information.

🎓 Learning Outcomes

This project demonstrates the use of Python libraries, data encoding, image generation, and basic project development.

👨‍💻 Author

Amit Maurya

📄 License

This project is created for educational and learning purposes.
