# KeoPy

**KeoPy** is a standalone Python module for generating and analysing **all-sky keograms** — time-compressed representations of sky imagery that reveal how celestial and atmospheric features evolve over time.

The project focuses on reliability, reproducibility, and flexibility, providing both a Python API and a command-line interface for automated or interactive analysis workflows.

## ✨ Key Goals

* Efficient generation of keograms from image sequences or video streams
* Support for common astronomical and imaging formats (FITS, RAW, JPEG, PNG, MP4)
* Configurable preprocessing, normalisation, and calibration pipelines
* Modular structure for scientific and creative use cases
* Reproducible metadata and output file standards
* Optional CLI for batch processing and nightly automation


## 🧪 Development

KeoPy uses **Poetry** for dependency and environment management.

```bash
git clone https://github.com/spudlab-xyz/keopy.git
cd keopy
poetry install
```

Run tests and quality checks:

```bash
poetry run pytest
poetry run ruff check .
poetry run black .
```

## 🪐 License

Licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

## 🧭 Project Status

KeoPy is currently **in active development**.
Functionality and APIs may change until the first stable release (`v0.1.0`).

## 💡 Support

If you have questions or need help:

- 📝 [Open an issue](https://github.com/spudlab-xyz/keopy/issues)
- 💬 Join our community discussions
- 📧 Contact us through our website

---

<div align="center">
  <strong>Built with ❤️ by the SpudLab community</strong>
</div>
