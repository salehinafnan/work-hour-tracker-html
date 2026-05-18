# Work Hour Tracker

A high-performance, premium, local-first client-side web application designed to track work hours, manage breaks, and visualize work analytics with precise IndexedDB-backed data persistence.

![Work Hour Tracker Clock Icon](https://raw.githubusercontent.com/salehinafnan/work-hour-tracker-html/main/index.html) *Served dynamically via Vercel*

---

## Key Features

* 🚀 **Local-First & Serverless**: Zero backend dependencies. Data is fully persisted in your browser via IndexedDB and LocalStorage, ensuring maximum privacy and instant load times.
* 🎨 **Dual Premium Themes**:
  * **Midnight (Premium Noir)**: A deep black interface with optimized contrast for low-light environments.
  * **Glass (Glassmorphism)**: A modern frosted-glass interface with vibrant ambient backdrops.
* ⏱️ **Atomic Work & Break Timers**: Accurately track active working sessions and rest breaks with responsive state management.
* 🎯 **Daily Goals & Progress**: Set target work and break duration with dynamic progress-rail indicator tracking.
* 📊 **Virtual List Logbook**: View tracking history with a high-performance virtualized list, featuring tagging, searching, and advanced date/status filtering.
* 🌍 **Timezone Selection**: Support for multiple timezones with precise tabular monospaced numbers.
* 💾 **Data Portability**: Export and import complete JSON backups of your tracking history to migrate across browsers or devices.

---

## Technology Stack

* **Structure & UI**: Semantic HTML5 & Vanilla CSS3 (Custom properties, blur filters, CSS Grid, Flexbox)
* **Logic**: Vanilla ES6+ JavaScript (Web Storage APIs, IndexedDB, dynamic DOM virtualization)
* **Fonts & Icons**: JetBrains Mono, Inter/Apple-System font family stack, Inline SVGs

---

## Deployment & Hosting

### Hosting on Vercel (Recommended)

This repository is optimized for one-click static hosting on **Vercel**:

1. Log in to [Vercel](https://vercel.com).
2. Click **Add New** > **Project** and import this repository.
3. Keep the default settings and click **Deploy**.
4. Enjoy a permanent HTTPS URL with automatic deployments on every `git push`.

---

## License

This project is open-source under the [MIT License](LICENSE).
