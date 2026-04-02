# 🌿 Solace – Empathy-first social platform

**Solace** is a mental health & emotional support community where people share their struggles, anxieties, wins, and grief – and receive genuine empathy, not likes or judgment. Unlike mainstream social media, Solace removes performance pressure and replaces it with compassion.

🔗 **Live Demo:** [Your Netlify/Vercel URL here]

---

## ✨ Key Features

- **Anonymous posting by default** – Share freely without fear of judgment. You can choose to reveal your identity per post.
- **Emotion tags instead of hashtags** – `#anxiety`, `#grief`, `#burnout`, `#win`, `#hope`… Context, not trends.
- **Empathy reactions (no likes)** – `🤝 I felt this`, `💪 Sending strength`, `🫂 You're not alone`, `🌟 Proud of you`. Counts show support, not popularity.
- **Community Rooms** – Join spaces like *Anxiety Corner*, *Grief Support*, *Celebrate Wins*, *Burnout Recovery*.
- **Private Journal + Mood Tracking** – Daily mood scale (1-7) and free writing. Charts show your weekly trend. Only you can see it.
- **AI Peer Support** – On any post, get a compassionate, non-clinical AI response (powered by Claude/GPT via simulated mock in demo, or real API in production).
- **Google Sign‑in & Profile Pictures** – Authenticate with your Google account. Upload a profile photo (like Facebook). Or use the app as a guest.
- **Privacy-first** – No follower counts, no infinite scroll, no algorithmic rage bait. Your data stays yours.

---

## 🛠️ Tech Stack

| Layer       | Technology |
|-------------|------------|
| Frontend    | React 18 (functional components, hooks) |
| Styling     | Tailwind CSS + custom design system |
| Auth + Storage | Firebase (Google Auth, Cloud Storage for profile pics) |
| Hosting     | Any static host (Netlify, Vercel, GitHub Pages) |
| AI (optional) | Anthropic Claude API / GPT-4 (via secure backend proxy) |

---

## 🚀 Getting Started (Local Development)

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/solace-platform.git
   cd solace-platform
