# Face Recognition System

## Overview
The Face Recognition System is an advanced application that utilizes deep learning techniques to detect and recognize faces in real time. This system is designed for authentication and security purposes, leveraging OpenCV and FaceNet for accurate facial recognition.

## Features
- Real-time face detection and recognition
- High accuracy using deep learning models
- Database integration for storing and retrieving facial embeddings
- User-friendly interface for registration and verification

## Technologies Used
- Python
- OpenCV
- TensorFlow/Keras
- FaceNet
- Flask (for web-based application)
- SQLite (for database management)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rajakashyap77/Face-Recoginition-System.git
   cd Face-Recoginition-System
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

## Usage
1. Register new users by capturing their facial features.
2. Store the facial embeddings in the database.
3. Perform face recognition by comparing live input with stored embeddings.

## Dataset
- The model uses pre-trained FaceNet embeddings.
- Custom datasets can be integrated for improved performance.

## Future Enhancements
- Improve accuracy with a larger dataset.
- Implement multi-user access control.
- Deploy as a cloud-based API service.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any issues or suggestions, feel free to reach out at [GitHub Issues](https://github.com/rajakashyap77/Face-Recoginition-System/issues).
