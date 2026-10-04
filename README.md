# Who's Missing? 🎈

A playful, ad-free visual comparison and working memory web game designed for toddlers (ages 2 to 4) to develop early cognitive skills through tactile play.

---

## 🎯 How It Works
1. **The Reference Set (Top Row):** Three bright, recognizable everyday objects (animals, fruits, vehicles, toys) appear in the top row.
2. **The Scrambled Puzzle (Bottom Row):** The bottom row presents the same set in a randomized, scrambled order—with exactly one item replaced by a glowing mystery box (`❓`).
3. **Interactive Spotting:** The toddler scans both rows, identifies which friend is absent below, and taps that item directly in the top row.
4. **Positive Reinforcement:** Correct choices smoothly reveal the missing item in the mystery box, accompanied by a celebration of colorful confetti, encouraging voice prompts, and musical chimes.

---

## ✨ Features
- **Toddler-First UX:** Jumbo, tactile 3D touch targets, zero reading required, and clean layouts built for small fingers on tablets and phones.
- **Working Memory & Executive Function:** Scrambling the bottom row challenges toddlers to compare sets rather than simply matching identical positions.
- **Gentle Pacing:** Features intentional completion holds and screen locks to allow toddlers to hear spoken praise and absorb the solution before moving on.
- **Voice-Ready:** Includes built-in musical fallback chimes alongside drop-in support for custom `.mp3` voice recordings.
- **100% Client-Side & Private:** Single-file static build with no tracking, external dependencies, or data collection.

---

## 📂 File Structure
```text
├── index.html
├── README.md
└── audio/
    ├── welcome.mp3  # "Let's play!"
    ├── prompt.mp3   # "Look at the top row! Who is missing below?"
    ├── correct.mp3  # "Awesome! You found the missing friend!"
    └── wrong.mp3    # "Oops, not that one! Look again!"
