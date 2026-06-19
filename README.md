<div align="center">

# 🩺 MediBook

**A doctor appointment booking experience, built entirely in one HTML file.**

No backend. No build step. No frameworks. Just HTML, CSS, and vanilla JavaScript — with a clickable desk-lamp intro for good measure.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://github.com/yaswanthsurya-99/FEDF)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://github.com/yaswanthsurya-99/FEDF)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://github.com/yaswanthsurya-99/FEDF)
[![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat&logo=greensock&logoColor=black)](https://gsap.com/)
![No backend](https://img.shields.io/badge/backend-none-lightgrey)
![Status](https://img.shields.io/badge/status-demo%2Flearning%20project-orange)

</div>

---

## Preview

<div align="center">
<img src="assets/screenshot-login.png" width="800" alt="MediBook login screen with the lamp-toggle intro" />

<sub><em>Click the lamp to bring the login screen to life.</em></sub>
</div>

<br/>

<table>
<tr>
<td width="50%"><img src="assets/screenshot-dashboard.png" alt="MediBook patient dashboard" /></td>
<td width="50%"><img src="assets/screenshot-doctors.png" alt="MediBook find doctors page" /></td>
</tr>
<tr>
<td align="center"><sub>Patient dashboard — health overview, metrics, recent activity</sub></td>
<td align="center"><sub>Find Doctors — browse by specialisation and book directly</sub></td>
</tr>
</table>

---

## ✨ Features

| | |
|---|---|
| 🪔 **Animated entrance** | A clickable desk-lamp toggle lights up the scene before the login form appears |
| 🔐 **Auth (client-side)** | Register and sign in as a patient — session & user data persisted via `localStorage` |
| 📊 **Dashboard** | Personalized greeting, live date, upcoming appointments, and mock health metrics (BP, blood sugar, cholesterol, BMI) |
| 📅 **Book Appointment** | Pick a specialisation → doctor → type → date → time slot, then confirm |
| 👨‍⚕️ **Find Doctors** | Browse specialists grouped by department, with ratings & availability badges |
| 🗂️ **Medical Records** | Appointment history, lab reports, prescriptions, imaging, and vaccination record |
| 📱 **Single-page navigation** | Smooth in-app routing, modals, and toasts — all vanilla JS, no router library |

## 🛠️ Tech Stack

- **HTML5 / CSS3** — entire UI in one file, custom properties for theming
- **Vanilla JavaScript** — page routing, auth, booking logic, DOM rendering
- **[GSAP](https://gsap.com/)** — intro animation (via CDN)
- **Google Fonts** — Syne (display) + DM Sans (body)
- **`localStorage`** — the entire "database" for users and appointments

## 📂 Project Structure

```
FEDF/
├── index.html   # Entire application — markup, styles, and scripts
└── assets/      # README screenshots
```

## 🚀 Getting Started

No installation or dependencies required.

```bash
git clone https://github.com/yaswanthsurya-99/FEDF.git
cd FEDF
```

Then either:

- **Just open it** — double-click `index.html`, or
- **Serve it locally**
  ```bash
  python3 -m http.server 8000
  ```
  and visit `http://localhost:8000`

Click the lamp → **Register** a new patient → sign in → explore the dashboard, book an appointment, and browse doctors.

> 💾 Account and appointment data live only in your browser's `localStorage`. Clearing site data resets the app to a blank slate.

## ⚠️ Disclaimer

This is a **front-end demo / learning project** for practicing UI design, animation, and client-side state management. Doctors, health metrics, prescriptions, and lab results shown are sample data — **not real medical information** — and there is no real authentication security, encryption, or backend persistence.

## 📄 License

No license specified yet. Add one (e.g. [MIT](https://choosealicense.com/licenses/mit/)) if you'd like others to reuse this code.

---

<div align="center">
<sub>Built as part of a Front-End Development (FEDF) coursework project.</sub>
</div>
