## Hi there 

I'm a Software Engineer with experience in Embedded Systems, Edge Computing, ML Systems and Developer Tooling.
- Cybernetic Electronics Engineering (2020-2024), CETYS Universidad.
- I'm interested in AI, Compilers, Edge Computing and Software Infrastructure.
- Contributed to the open-source [Torq Compiler](https://github.com/synaptics-torq) as [tomas-synaptics](https://github.com/tomas-synaptics). Selected work:
  - **Tooling.** Built a tool for [static shape conversion of TFLite models](https://github.com/synaptics-torq/torq-tools/commit/4860ec7513dac7bb99295c94ed6a5724ac257e96), preparing neural networks for compilation (moved to the [torq-compiler](https://github.com/synaptics-torq/torq-compiler/blob/main/python/torq/lab/model_tools/shape_conversion/tflite.py) repo).
  - **Compiler optimization.** Added a transform that [rewrites `pow(x, 0.5)` as `sqrt`](https://github.com/synaptics-torq/torq-compiler/commit/2d6c61d5daf8d704f0cfe355c008e79f2bb66b53) to enable correct NSS hardware support.
  - **Pass-pipeline cleanup.** Removed dead lowering paths ([unused TosaToTorqHL patterns](https://github.com/synaptics-torq/torq-compiler/commit/fd8755318af365b98eb3b1b276643fd4272f7d34), [PromoteScalarsTo1D](https://github.com/synaptics-torq/torq-compiler/commit/eff44d1f2dab6120a232765f1d877cfe7046ac03)) to simplify the compiler and solve bugs.
  - **Test infrastructure.** Sped up ONNX per-layer testing with [result caching](https://github.com/synaptics-torq/torq-compiler/commit/c4947ee10bb48367160d0acdfb458d1ce66b38d9) and [lazy model loading](https://github.com/synaptics-torq/torq-compiler/commit/76285f5d466b5a79ae0a347d4d184f3d05759961).

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)

**Also worked with**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![8051 Assembly](https://img.shields.io/badge/8051%20Assembly-6E4C13)

