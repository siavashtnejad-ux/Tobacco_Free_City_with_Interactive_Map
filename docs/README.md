# Tobacco-Free City Assessment with Interactive Map

A Persian-language tobacco-free city assessment tool enhanced with interactive geographic results and Google Sheets submission.

The browser-based application helps evaluators complete a structured checklist, calculate a city score, preserve progress locally, and view geographic performance feedback.

## Features

- Interactive tobacco-free city checklist
- Automatic score and progress calculation
- Persian right-to-left interface
- Jalali date selection
- Local browser persistence
- Interactive geographic result visualization
- Google Sheets submission integration
- Printable and PDF-oriented report output
- Responsive single-page design

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Google Apps Script / Google Sheets
- Inline geographic visualization
- Vazirmatn font

## Run Locally

```bash
git clone https://github.com/siavashtnejad-ux/Tobacco_Free_City_with_Interactive_Map.git
cd Tobacco_Free_City_with_Interactive_Map
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Google Sheets Setup

To enable remote submission, connect the frontend to a deployed Google Apps Script web app. The script should validate incoming fields before appending them to the spreadsheet.

Keep private credentials out of frontend code. Add clear user consent and a privacy notice before collecting identifying information.

## Deployment

The project is a static single-page application and can be hosted on GitHub Pages or another static hosting service.

## Author

[Siavash Torkamannejad](https://github.com/siavashtnejad-ux)
