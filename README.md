# YouTube to MP4 Converter

Free, clean YouTube video downloader. No ads. No spam. Just download.

## Tech Stack

- **Frontend:** Next.js + React
- **Backend:** Node.js serverless (Vercel)
- **Conversion:** yt-dlp
- **Storage:** Temp files (cleaned up after download)

## Setup & Installation

### Local Development

1. **Clone/download this project**
```bash
   cd youtube-mp4-converter
```

2. **Install yt-dlp** (required)
   
   **Ubuntu/Debian:**
```bash
   sudo apt update
   sudo apt install yt-dlp
```

3. **Install Node dependencies**
```bash
   npm install
```

4. **Run development server**
```bash
   npm run dev
```

   Open http://localhost:3000 in your browser.

5. **Test the converter**
   - Paste a YouTube URL
   - Click "Download"
   - Should download as MP4

## Deployment to Vercel

See README for details on hosting (requires yt-dlp setup).
