# 🧾 PaperBright — Clean & Restore Scanned Documents with Python

**PaperBright** is a lightweight Python tool to clean up scanned documents like result cards or certificates. It whitens dull backgrounds, sharpens blurry or distorted text, and preserves any embedded images or stamps — all without relying on paid apps like CamScanner or Adobe Scan.

---

## ✨ Features

- 🧼 **Clean Background**: Brightens dull, gray, or noisy paper backgrounds to clean white.
- ✒️ **Text Restoration**: Attempts to fix blurry or distorted text using sharpening, contrast, and deblurring techniques.
- 🖼️ **Image Preservation**: Skips enhancement in specific pixel areas (like photos or logos).
- 🎯 **Selective Correction**: Apply processing only on selected regions or avoid specific coordinates.
- 🐍 Pure Python using **OpenCV** and **NumPy** — no paid API or tool required.

---

## 📸 Use Cases

- Enhancing **result cards**, **transcripts**, **certificates**, and **official documents**.
- Preparing documents for **OCR** or digital archiving.
- DIY alternative to **CamScanner Premium**, **Adobe Scan**, or other paid apps.

---

## 🧠 Why I Built It

Most mobile scanning apps lock the best features behind a **paywall**. So I built this in my **free time** to clean up a blurry result card using just Python — and it turned out surprisingly well.

---

<h1>📦 Installation</h1>
1. Clone the repository:

```bash
git clone https://github.com/your-username/paperbright.git
cd paperbright
```

2. Install the required libraries:
```
1. opencv-python
2. numpy
3. scipy
```
<h1>🔧 Techniques Used </h1>
<h2> CLAHE (Contrast Limited Adaptive Histogram Equalization) </h2>
<h2> Adaptive thresholding </h2>
<h2> Deblurring via Wiener filter </h2>
<h2> Morphological filtering </h2>
<h2> Edge-preserving enhancement </h2>
<h2> Region masking</h2>
