# CBSE & Karnataka Board (KSEAB) Multi-Subject Quiz (Classes 7 to 10)

A zero-dependency, responsive single-file web application (`index.html`) built for students studying under **CBSE (NCERT)** and **Karnataka State Board (KSEAB / DSERT)** across **Classes 7, 8, 9, and 10**.

## Key Features

- **Cross-Platform Responsive Design:** Fluid layout (`100dvh`, `env(safe-area-inset-*)`) optimized for Android smartphones, Windows PCs, and Apple iOS/macOS devices.
- **Dual Curriculum & Multi-Class Support:** Instant switching between **CBSE (NCERT)** and **Karnataka State Board (KSEAB)** across **Class 7, Class 8, Class 9, and Class 10**.
- **Comprehensive Subject Coverage:** Includes **Mathematics**, **Science**, **Social Science**, **English**, and **ಕನ್ನಡ (Kannada)** rendered in authentic Kannada script for both CBSE and KSEAB.
- **Customizable Question Count (10 to 100):** Interactive slider supporting **10, 20, 40, 80, or 100** questions per session.
- **Repeated Question Indicator:** Automatically highlights recurring questions in longer practice sessions with a **`🔁 Repeated Question`** badge.
- **Configurable Countdown Timer & Pause Mode:** Adjustable session timer from **0 minutes (untimed)** up to **60 minutes (1 hour)** with a **Pause / Resume** toggle that hides active question content while paused.
- **Detailed Answer Breakdown & Hints:** On-demand hints plus option-by-option explanations showing why both incorrect and correct choices apply.
- **Session Analytics & Report Exports:** End-of-session score circle, speed metrics, subject-wise accuracy bars, and one-click downloads for **PDF** and **Word (`.doc`)** reports.
- **Custom Question Manager (`➕ Add Questions`):** Add new questions directly in the browser (persisted in `localStorage`) or export custom question sets as JSON.

---

## Project Structure

Keep your repository clean with two files at the root level:

```text
cbse-kseab-quiz-7to10/
├── index.html   # Complete self-contained quiz application
└── README.md    # Documentation and deployment guide
