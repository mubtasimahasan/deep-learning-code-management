In this project, we delve into effective code management practices for deep learning projects. The code for the session is implemented in Python using PyTorch and PyTorch Lightning framework, utilizing various packages for data processing and model training.

  
## 📂 Project Structure
  
-  **`code/`**: Contains the code examples and exercises.

-  **`data/`**: Data modules with train, val, and test dataloaders, including data preparation and splitting files using PyTorch Lightning.

-  **`configs/`**: YAML files containing arguments for different components.

-  **`models/`**: Model definitions for training, validation, and testing, as well as logic for optimizer, LR scheduler, score metric, and loggers.

-  **`utils/`**: Necessary functions and classes to load config files and other utilities.

-  **`cli.py`**: Command line interface for training and testing experiments.

-  **`__data__/`** (optional): Temporary folder to download the dataset.

-  **`__logs__/`** (optional): Temporary folder to store checkpoints, logs, and other experiment-related information.

  
## 🛠️ Libraries and Dependencies

The project is implemented in Python using PyTorch and PyTorch Lightning framework, along with the following packages:

-  `albumentations==1.3.1`

-  `click==8.1.7`

-  `numpy==1.26.4`

-  `Pillow==9.3.0`

-  `Pillow==10.2.0`

-  `pytorch_lightning==2.0.9.post0`

-  `PyYAML==6.0.1`

-  `torch==2.1.1+cu118`

-  `torchmetrics==1.2.0`

-  `torchvision==0.16.1+cu118`

