# 🖼️ Image Resizer Tool (Batch Processor)

A simple Python tool to **resize and convert multiple images** in a folder using the `Pillow` library. Automate image tasks like standardizing dimensions or preparing for web uploads.

---

## 📌 Features

- ✅ Batch resize all images in a folder
- ✅ Convert image formats (e.g., PNG → JPG)
- ✅ Set custom dimensions and output quality
- ✅ Works with JPG, PNG, WebP, BMP, etc.

---

## ⚙️ How It Works

1. Reads all images from the `images/` folder.
2. Resizes them to the defined target size (default: `800x800`).
3. Converts the format (default: `JPEG`) and saves them to the `resized/` folder.

---

## 📚 What You’ll Learn

To understand and modify this project, you'll need:

- Basics of **Python scripting**
- File operations using the `os` module
- Image processing with **Pillow** (`PIL`)
- Exception handling and directory automation

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/image-resizer-batch-tool.git
cd image-resizer-batch-tool
