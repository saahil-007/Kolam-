# Kolam: Generative Art Platform

Kolam is a web-based platform for creating and exploring generative art inspired by traditional Kolam patterns. This application allows users to generate intricate designs, customize their appearance, and share their creations.

## Features

- **Generative Art:** Automatically generate complex and beautiful Kolam-style patterns.
- **Customization:** Adjust parameters such as color, complexity, and symmetry to personalize the artwork.
- **Interactive UI:** A modern and intuitive interface built with React, Vite, and ShadCN UI.
- **FastAPI Backend:** A high-performance backend powered by FastAPI to handle image generation and processing.
- **Real-time Previews:** See the generated artwork update in real-time as you adjust the settings.

## Tech Stack

- **Frontend:**
  - React
  - Vite
  - TypeScript
  - ShadCN UI
  - Tailwind CSS

- **Backend:**
  - FastAPI
  - Python
  - OpenCV
  - PyTorch

## Getting Started

### Prerequisites

- Node.js and npm
- Python 3.8+ and pip

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saahil-007/Kolam-.git
   cd Kolam-
   ```

2. **Install frontend dependencies:**
   ```bash
   cd frontend
   npm install
   ```

3. **Install backend dependencies:**
   ```bash
   cd ../backend
   pip install -r requirements.txt
   ```

### Running the Application

1. **Start the backend server:**
   ```bash
   cd backend
   uvicorn main:app --reload
   ```
   The backend will be available at `http://127.0.0.1:8000`.

2. **Start the frontend development server:**
   ```bash
   cd frontend
   npm run dev
   ```
   The frontend will be available at `http://localhost:5173`.

## Usage

- Open your browser and navigate to `http://localhost:5173`.
- Use the controls in the sidebar to customize the generated Kolam pattern.
- Save or share your favorite creations.