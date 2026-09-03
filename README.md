# Yu_Repo_Sep2026

[![Tests](https://img.shields.io/badge/tests-passing-brightgreen.svg)]()
[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)]()
[![C++](https://img.shields.io/badge/C%2B%2B-17%2F20-orange.svg)]()
[![FPGA/HLS](https://img.shields.io/badge/AMD-Vitis%20HLS-red.svg)]()

> **Personal Engineering & Research Repository:** Dedicated workspace for AI-on-FPGA implementation, High-Level Synthesis (HLS) hardware kernels, deep learning models, and automated testbenches.

---

## 📁 Repository Structure

```text
Yu_Repo_Sep2026/
├── src/                    # Primary source code (Python & C++ modules)
│   ├── __init__.py
│   └── main.py             # Core pipeline entry point
├── tests/                  # Automated unit test suites & testbenches
│   ├── __init__.py
│   └── test_basic.py       # Base regression tests
├── .gitignore              # Clean ignore rules for Python, C++, and Vitis HLS
└── README.md               # Repository documentation
```

---

## 🛠️ Toolchains & Environment

* **Python:** 3.10+ (PyTorch, NumPy, ONNX)
* **C++:** C++17 / C++20 standard
* **FPGA / Acceleration:** AMD Vivado & Vitis HLS (Targeting Versal AI Edge / Zynq UltraScale+)

---

## 🧪 Running Tests

Run the automated test suite locally:

```bash
# Using standard Python unittest
python -m unittest discover -s tests -p "test_*.py"

# Or using pytest (if installed)
pytest tests/
```

---

## 📜 Development Workflow

1. Create a feature branch: `git checkout -b feature/<feature-name>`
2. Implement code in `src/` and corresponding verification in `tests/`
3. Verify all tests pass: `python -m unittest`
4. Commit with clear conventional commit messages: `git commit -m "feat(...): ..."`
5. Push to GitHub: `git push origin <branch-name>`