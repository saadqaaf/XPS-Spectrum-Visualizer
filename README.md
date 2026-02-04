# 📉 Binding Energy Spectrum Visualizer

A linear, interactive visualization tool for exploring the entire X-ray Photoelectron Spectroscopy (XPS) binding energy range. Unlike standard tables, this tool maps energies from 0 eV to 120,000 eV on a continuous scale, helping users visualize peak distribution and overlaps.

## 🚀 Features

- **Linear Energy Scale**: A continuous axis visualizing the entire spectrum, allowing you to see exactly where peaks fall relative to one another.

- **Deep Zoom & Pan**:
  - **Survey View**: See the full 0–120 keV range.
  - **Detail View**: Zoom in to specific regions (e.g., the standard Al Kα range of 0–1487 eV) using the slider.

- **Interactive Markers**: Hover over any peak marker to reveal:
  - Element Name & Symbol
  - Orbital (e.g., 4f 7/2)
  - Precise Binding Energy (eV)

- **Fingerprint Highlighting**: Primary identification lines ("fingerprints") are visually taller and highlighted in gold to distinguish them from secondary peaks.

- **Real-time Search**: Type an element symbol (e.g., "Au") to instantly highlight all associated peaks on the timeline, making it easy to see an element's entire spectral footprint.

## 🛠️ Usage

This tool is a Single-File Application (SPA) using HTML5 Canvas. It runs entirely in the browser with no external dependencies.

### Run Locally

1. Download the `index.html` file.
2. Open it in any modern web browser.

### Host Online (GitHub Pages)

1. Fork or upload this repository to your GitHub account.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, select `main` from the branch dropdown and click **Save**.
4. Your tool will be live at:
   ```
   https://sadegh-ghorbanzadeh.github.io/XPS-Spectrum-Visualizer/
   ```

## 💻 Tech Stack

- **HTML5** structure.
- **Canvas API** for high-performance rendering of spectral lines.
- **JavaScript (ES6+)** for logic and interactivity.
- **Tailwind CSS** (via CDN) for responsive styling.

## 📄 License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software.

---

**Note**: This visualization tool is designed for educational and research purposes. For quantitative analysis, always refer to calibrated instruments and primary reference data.
