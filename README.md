# Document Scanner Using OpenCV

## Overview

This Python project demonstrates the implementation of a document scanner using OpenCV, an open-source computer vision library. The program takes an input image containing a document, detects its contours, applies perspective transformation to obtain a top-down view, and finally applies local thresholding to enhance the document's readability.

## Dependencies

- `numpy`: Numerical computing library for array manipulation.
- `argparse`: Command-line argument parsing.
- `cv2` (OpenCV): Computer vision library for image processing.
- `imutils`: Convenience functions to make basic image processing operations simpler.

## Usage

1. Run the script `Cscanner.py`.
2. Pass the input image path using the `-i` or `--image` argument.

```bash
python Cscanner.py --image <path_to_input_image>
```
