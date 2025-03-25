# QR Code Authentication

Detects counterfeit QR codes using machine learning.

## Step-by-step Process

1. **Prepare your dataset**:
   - Compress your QR code folder into a ZIP file named:  
     `Assignment Data-20250324T021523Z-001.zip`  
     *(Original folder should contain "First Print" and "Second Print" subfolders)*

2. **Run the notebook**:
   - Google Colab: Upload the ZIP and open `QR_Code_Authentication.ipynb`
   - Local: Clone repo and place ZIP in the folder before running:
     ```bash
     git clone https://github.com/yourusername/qr-auth.git
     cd qr-auth
     jupyter notebook QR_Code_Authentication.ipynb
     ```

The notebook will automatically:  
- Install dependencies  
- Extract the ZIP  
- Train and evaluate models  
