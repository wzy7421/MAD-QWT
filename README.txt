# MAD Framework: Multi-Q Gabor Wavelet Perception

This repository contains the Python implementation of the Q-factor Wavelet Transform (QWT), Super-Resolution Averaged Projection (SRAP), and Minimum Intensity Projection (MinIP) utilized in our autonomous driving perception framework (MAD).

## Project Structure
- `main.py`: The main execution script to reproduce the time-frequency enhancement visualizations.
- `qwt_core.py`: Core algorithms for QWT, SRAP, and MinIP.
- `data_utils.py`: Signal preprocessing, FFT, and the Synthetic Signal Generator (described in Appendix A).
- `requirements.txt`: Python dependencies.

## Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Run the demo: `python main.py`

**Note:** If the private sensor dataset (`data7.mat`) is not placed in the root directory, the script will automatically fallback to generating the multi-component synthetic signal defined in the paper's **Appendix A** for methodological validation.