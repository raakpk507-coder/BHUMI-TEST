# BHUSMART 📚

> Bhumi Smart Question Tracker — NCERT question tracking PWA

## Features
- Student-wise question tracking
- Smart Paper Generator (auto-selects fresh/weak questions)
- Forgetting curve — wrong question review scheduler
- Download paper as ZIP or individual images
- Re-download any past paper from History
- GitHub sync — data saved to this repo
- Installable PWA (works offline)

## Setup
1. Open `index.html` in browser
2. Go to **Settings**
3. Enter your GitHub Personal Access Token (`repo` scope)
4. Hit **Save Token & Sync**

## Files
| File | Purpose |
|------|---------|
| `index.html` | Main app |
| `manifest.json` | PWA manifest |
| `sw.js` | Service worker (offline support) |
| `bhusmart_data.json` | Auto-saved data (do not edit manually) |

## GitHub Token
`GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic) → Generate → tick repo → Copy`
