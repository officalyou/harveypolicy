
# Harvey Full Final (Desktop + Mobile)

## Features
- Working Python backend (TTS + state sync)
- Web avatar UI (face reacts + speaks)
- Electron desktop app (auto-start backend)
- Capacitor mobile-ready project

## QUICK START

### 1. Install deps
pip install TTS sounddevice numpy flask

### 2. Run backend
python backend/app.py

### 3. Run frontend
cd client
python -m http.server 3000

### 4. Desktop
npm install
npm start

### 5. Mobile (Android)
npx cap copy
npx cap open android
