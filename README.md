# AI Object Detector with Next js 14, Tailwind CSS, Tenserflow, React 

This application implements real-time object detection using a webcam feed with TensorFlow.js and the COCO-SSD model. The application captures video from the user's webcam, processes each frame to detect objects, and overlays the detection results on a canvas.

## Features

- **Real-Time Object Detection:** Leverages the COCO-SSD model to detect and label objects in real-time.
- **Webcam Integration:** Uses the webcam to provide a live video feed, making it easy to experiment with different environments and scenarios.
- **Dynamic Overlays:** Displays bounding boxes and labels for detected objects directly on the video feed.
- **Lightweight and Efficient:** Built with Next js 14,  Tailwind CSS and TensorFlow.js, ensuring a smooth and responsive experience in the browser.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ritammaity55/ai-object-detector.git
2. **Change the directory to the following folder:**
    ```bash
    cd .\ai-object-detector\
3. **Install dependencies:**
    ```bash
    npm install
    npm install react-webcam
    npm install @tensorflow-models/coco-ssd @tensorflow/tfjs
4. **Run the development server:**
   ```bash
    npm run dev
