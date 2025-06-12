# Helmet_Detection

In this model i have used yolov11n.pt model to train my model on basis of provided dataset. It detects whether the rider has helmet or not There are diffrent classes {0,1,2,3} 0:Number plate 1:No Helmet 2:With helmet 3:Rider
| Component               | Specification                                                              |
| ----------------------- | -------------------------------------------------------------------------- |
| **Processor (CPU)**     | Intel Core i5 (8th Gen or above) / AMD Ryzen 5 (or equivalent)             |
| **RAM**                 | 8 GB (minimum), 16 GB recommended for smoother multitasking                |
| **Storage**             | At least 100 GB free SSD space (for model weights, dataset, and outputs)   |
| **Graphics Card (GPU)** | NVIDIA GPU with CUDA support (GTX 1050 Ti or higher) *(for training YOLO)* |
| **Operating System**    | Windows 10 / Ubuntu 20.04 LTS or later                                     |
| **Python Version**      | Python 3.8 or above                                                        |
| **CUDA & cuDNN**        | CUDA Toolkit 11.3 or higher *(if GPU acceleration is used)*                |
| **Additional Software** | - PyTorch (YOLOv11)                                                        |

 - PaddleOCR dependencies  
 - OpenCV    
 - Flask/Django (if deploying as web app)  
 - MongoDB (for database)

If you plan to train models locally, a GPU is highly recommended.

For just inference, you can run YOLOv11 and PaddleOCR on CPU, though it will be slower.

Cloud platforms (e.g., Google Colab, AWS EC2 with GPU) are suitable alternatives for training/deployment.
