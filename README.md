# whl

[![PyPI](https://img.shields.io/pypi/v/sglang-kernel)](https://pypi.org/project/sglang-kernel/)

This repository hosts the **wheel index page** for [SGLang](https://github.com/sgl-project/sglang) packages. It is not the source code repository — it serves as a [PEP 503](https://peps.python.org/pep-0503/)-compatible package index for distributing pre-built wheels.

## Usage

- **Install a kernel package with a specific CUDA version:**
  ```bash
  pip install sglang-kernel --index-url https://docs.sglang.io/whl/cu129
  ```

- **Install nightly builds:**
  ```bash
  pip install sglang --index-url https://docs.sglang.io/whl/nightly/cu129
  ```

- **Browse available wheels:** Visit the [GitHub Releases](https://github.com/sgl-project/whl/releases) page, where all binary wheel files are hosted.
