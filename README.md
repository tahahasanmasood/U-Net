# Image Denoising using U-Net
This repository demonstrates the use of a U-Net architecture for image denoising. Gaussian noise is first added to clean images, and the noisy images are then passed through the U-Net model for effective denoising.

![U-Net_Image_Denoising](https://github.com/user-attachments/assets/5550fa33-c3f0-4957-87d0-60cf0635c368)

## Dataset
CelebA-HQ dataset is used containing 30,000 high-quality celebrity faces with a resolution of 256x256. The dataset is divided into 15,000 training, 10,000 validation, and 5,000 testing images. It can be downloaded from https://www.kaggle.com/datasets/badasstechie/celebahq-resized-256x256

```bash
└── Your_Data_Dir
   ├── Training
   ├── Validation
   ├── Testing
```

## Usage
The experiment is performed with fixed Gaussian Noise and random Gaussian Noise in the training process. 
- Demo: Example demo code is provided at `demo_fixed_noise`
- Fixed Noise:`fixed_noise`
- Random Noise:`random_noise`

## Reference
https://stanford.edu/class/ee367/Winter2019/dua_report.pdf
