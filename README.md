# Fernly — Team Workspace Dashboard

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/fernly-dashboard-animations/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable frontend reconstruction of the uploaded **29.5-second** screen recording (720 × 1280, 30 fps).

## Run
1. Extract `fernly-dashboard-animations.zip`.
2. Open `index.html` in Chrome, Edge, Firefox or Safari.
3. Use the left sidebar to switch between Dashboard, Tasks, Calendar, Analytics, Team and Settings.
4. Try dragging tasks between Kanban columns, changing team filters, editing the calendar month and changing the appearance accent.
5. Start, pause or stop the dashboard time tracker.

No npm install, build step, backend, API key or server is required.

Optional local server:
```bash
python3 -m http.server 8000
```
Open `http://localhost:8000`.

## What is visible in the video

The recording is titled **Dashboard Animations!** and presents a product called **Fernly** in a white/soft-grey workspace framed by a deep forest-green background. The profile shown is `Noah Castell` (`noah@fernly.app`). Sidebar entries:
- Dashboard
- Tasks
- Calendar
- Analytics
- Team
- Settings
- Help
- Logout

A mobile-app promotion card reads **Fernly for iOS & Android**.

### Dashboard
Visible summary cards:
- Tasks Completed: 24
- Overdue Projects: 10
- Running Projects: 12
- Pending Projects: 2

Other sections include Project Analysis, Team Collaboration, Recent Projects, Project Progress (42%) and a Time Tracker. The timer in the clip is around `01:24:08` and has pause and stop controls.

### Tasks
A four-column Kanban board:
- To do
- In progress
- In review
- Done

Filter chips include All, My tasks, High priority and Due this week. Visible examples include:
- Saved filters for projects
- Write API endpoint docs
- Onboarding email sequence
- Cut LCP under 2 seconds
- Design login & sign-up screens
- Passkey sign-in
- Marketing site refresh
- Q4 launch announcement
- Safari & Firefox regression pass
- Brand illustration set
- Monorepo cleanup
- Dashboard analytics widgets

### Team
Team filter chips include All, Engineering, Design, Marketing and Management. Visible team cards include Priya Raman (Product Designer) and Maya Kovac (Brand Designer), with open tasks, completed tasks, workload, Message and Profile controls.

### Calendar
The recording shows an October 2026 calendar with a selected Saturday, October 3, a day agenda and an upcoming list.

### Analytics
The Analytics screen includes a Throughput graph described as tasks completed per day, 7-day average, against the previous period. It compares this period with the previous period.

### Settings
Settings contains Profile, Notifications and Appearance. The Appearance panel offers accent themes Forest, Ocean, Plum and Ember, plus Sunday/Monday week-start choices. The clip demonstrates changing the accent to Ocean.

## Source-code extraction note

Unlike some code-demo recordings, this video does **not** show an editor, source-code panel, or readable HTML/CSS/JavaScript snippets. It shows the running Fernly dashboard and UI interactions only. Therefore no original source code can honestly be transcribed from this video. The supplied `index.html`, `styles.css` and `app.js` are a fresh implementation reconstructed from the visible screens and behavior, not the original Fernly repository.

## Included functionality
- Responsive Fernly-style workspace layout and sidebar navigation.
- Dashboard summary metrics, project analysis bars, team list, project progress gauge.
- Running timer with start, pause and stop.
- Four-column task board with drag-and-drop between stages.
- Task filters: All, My tasks, High priority, Due this week.
- Team directory and department filters.
- October 2026 calendar, month navigation and Sunday/Monday week-start preference.
- Analytics throughput chart.
- Settings sections: Profile, Notifications and Appearance.
- Four live accent themes: Forest, Ocean, Plum and Ember.
- Demo create-task, create-project, invite-member and new-event dialogs.
- Search navigation and toast feedback.

## Files
- `index.html` — app shell, sidebar and modal.
- `styles.css` — visual design, charts, Kanban board, calendar, cards and responsive layout.
- `app.js` — sample workspace data, navigation, interactions and timer.
- `README.md` — screen observations and run guide.

## Limitations
This is a frontend-only demo. No real users, authentication, cloud persistence, project API, calendar sync, team messaging, notifications service, mobile app download, or time-tracking backend is connected. Changes and timer state live only in the current browser session. Data not clearly readable in the short video has been filled with illustrative sample content.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
