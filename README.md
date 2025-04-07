# Ghibli Photo Converter

A fun AI-powered app that transforms your photos into Studio Ghibli-style art ✨

## 🚀 Project Structure

- `frontend/` - Static website (HTML/CSS/JS)
- `backend/` - FastAPI app that handles image uploads and "converts" them (simulate Ghibli effect)

## 🔧 Local Development

1. Start backend:
   ```bash
   cd backend
   pip install -r requirements.txt
   uvicorn ghibli_backend:app --reload
   ```

2. Open `frontend/index.html` in your browser.

## 🌐 Deployment

- **Backend:** Use [Render.com](https://render.com)
- **Frontend:** Deploy `frontend/` folder via GitHub Pages
