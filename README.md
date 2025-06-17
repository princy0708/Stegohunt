# 🕵️‍♀️ StegoHunt

StegoHunt is a Flask-based web tool that detects **LSB steganography** in images using entropy analysis. It helps digital forensics professionals and CTF players identify hidden data inside PNG, JPG, JPEG, and BMP images.

![StegoHunt Banner](https://your-image-link-if-any)

---

## 🚀 Features

- 🔍 Upload and analyze images for hidden LSB data
- 📊 Visual entropy calculation
- 📁 Generates downloadable JSON report
- 🌐 Built with Flask, NumPy, Pillow, and Matplotlib

---

## 📸 Screenshots

| Upload Image | LSB Visualization |
|--------------|-------------------|
| ![upload](screenshots/upload.png) | ![result](screenshots/result.png) |

---

## 🛠 Tech Stack

- Python 3
- Flask
- NumPy
- Pillow
- Matplotlib
- HTML5 + CSS3 (Jinja Templates)

---

## 🧪 Run Locally

```bash
git clone https://github.com/yourusername/StegoHunt.git
cd StegoHunt
pip install -r requirements.txt
python app.py
# Stegohunt
