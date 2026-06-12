# Genomic Variant AI Predictor UI

Simple frontend for genomic variant prediction using a remote ML model.

## Run with Docker

### Build
docker build -t genomic-ui .

### Run
docker run -p 8080:80 genomic-ui

Open: http://localhost:8080

## Important
- Replace the ngrok URL inside index.html before running
- Ensure your backend API is live

## Deploy Options
- GitHub → Render / Railway / Fly.io
- GitHub Pages (only UI, no Docker)
