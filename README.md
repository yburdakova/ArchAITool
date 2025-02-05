# ArchAiTool

## Overview
**ArchAiTool** is a desktop application built with **Electron.js, React, and Python** that integrates **Kraken OCR** for image processing and model training. The application consists of two main components:

1. **OCR Processing Module** - Uses trained models to extract text from images.
2. **Model Training Module** - Allows users to train OCR models using their datasets to improve recognition accuracy.

## Features
- 🖼 **OCR Processing**: Upload images and extract text using Kraken OCR.
- 🎓 **Custom Model Training**: Train your own models using labeled datasets.
- 🚀 **Electron-based UI**: Cross-platform desktop application with an intuitive interface.
- 🔗 **React & Vite Frontend**: Modern frontend with fast rendering and easy customization.
- ⚡ **IPC Communication**: Electron’s main and renderer processes communicate efficiently.
- 🐍 **Python Backend**: Handles OCR and training functionalities.

## Project Structure
```
/ArchAiTool
│── /src
│   ├── /main             # Electron backend
│   ├── /renderer         # React-based frontend
│   ├── /ocr-service      # Kraken OCR integration
│   ├── /training-service # Model training scripts
│── /public               # Static assets
│── package.json          # Node.js dependencies
│── README.md             # Project documentation
```

## Installation
### Prerequisites
- **Node.js** 
- **Python** 
- **Kraken OCR**

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yburdakova/ArchAiTool.git
   cd ArchAiTool
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the application:
   ```sh
   npm run dev
   ```

## Usage
- **OCR Processing**: Drag & drop images to extract text.
- **Training Module**: Upload labeled datasets and train models.
- **Settings**: Adjust OCR configurations and manage trained models.

## Technologies Used
- **Frontend**: React, Vite, TailwindCSS
- **Backend**: Electron, Node.js
- **OCR Engine**: Kraken OCR (Python-based)
- **Database**: SQLite (if required for training history)

## Author
- **Name**: Yana Burdakova
- **Email**: burdakovacom@gmail.com
- **Portfolio**: [burdakova.com](https://burdakova.com)
- **GitHub**: [Yana's GitHub](https://github.com/yburdakova)
- **LinkedIn**: [Yana's LinkedIn](https://www.linkedin.com/in/yana-burdakova/)

## License
This project is licensed under the **MIT License**.

## Contributing
Contributions are welcome! Feel free to submit issues and pull requests.

