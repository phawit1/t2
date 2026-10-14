# PulseLab — Interactive Fitness Lab

## Included flow
1. Choose Vertical Jump, Push-up Test, or Plank Hold.
2. Read the tutorial and safety notes.
3. Press I'm Ready and see the 3–2–1–GO countdown.
4. Complete the timed test. Push-ups include a manual rep counter; Vertical Jump asks for the measured jump height after the timer; Plank records the held time.
5. Review the report and save it to the browser history.

## Run
- Open `index.html` in a modern browser for a local demo.
- To share with your instructor or run more reliably on iPad Safari, host the file on an HTTPS static host (GitHub Pages, Netlify, or your own HTTPS server) and open that URL in Safari.
- No installation, camera permission, or backend is needed for this version.

## Limitations to explain in the presentation
- This version does not use AI or the camera to detect pose, validate exercise form, or count repetitions automatically. Push-up reps are manually counted; vertical jump height must be measured and entered by the user.
- The countdown and timer run in the browser. Safari may throttle or pause JavaScript when the tab/app is backgrounded, so keep the page open during the test.
- The performance index uses simple illustrative caps (jump 60 cm, push-ups 40 reps, plank 60 sec). It is not a scientifically validated, age-/sex-adjusted norm or medical assessment.
- History is stored in this browser's localStorage on this device only. Clearing website data may remove it; there is no cloud sync.
- The timer is a demonstration aid, not a certified sports-testing instrument. Warm up and stop if you feel pain or dizziness.
