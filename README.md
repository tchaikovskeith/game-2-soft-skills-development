# Game 2: Soft Skills Development — The Soft Skills Studio

A self-contained, responsive browser game for **3 Years In, 3 Years Forward**.

## How to play
1. Enter your **name** and select your **UP CU** from the supplied 10 choices.
2. Click **I'm Ready**. The **five-minute timer starts immediately**.
3. Read each scenario.
4. Pick one of five **scrambled soft-skill cards**. Their order and letters are shuffled each round.
5. **Tap the letter tiles in the correct order** to unscramble the selected skill. Tap an answer tile to undo it. For **Problem-solving**, the hyphen is added automatically for display/scoring purposes; arrange only the letters.
6. Check your answer. To earn a point, you must select the skill that matches the situation **and** arrange its letters correctly.
7. Read the lesson, then advance. The game ends after five scenarios or when time expires.
8. Download a **JPG scorecard** showing your name, CU, score, completed rounds, and time left. No data is uploaded to a server.

## The five skills
Communication, Empathy, Collaboration, Adaptability, and Problem-solving.

## Customization
The `SKILLS` array in `index.html` contains all scenarios, lessons, skill names, and icons. Edit there to align questions with your final learning framework.

## GitHub Pages
Upload `index.html` and this README to a **new** repository and enable **Settings → Pages → Deploy from a branch → main → /(root)**. The site will be published at `https://<user>.github.io/<repo>/` after deployment completes.

## Technical details
No dependencies, backend, third-party scripts, tracking or external services. Scores and names remain inside the browser and locally generated JPG. Works offline after download. Includes keyboard-focus styling and reduced-motion behavior.