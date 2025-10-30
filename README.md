# Heartbeat Harmony

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/nisa4114/heartbeat-harmony)

Heartbeat Harmony is a visually stunning, single-page web application designed as a romantic and nostalgic gesture. The core of the experience is an interactive, animated vinyl record set against a retro-themed backdrop. The page prominently features the message 'Your heartbeat is my soundtrack' with a neon, glitchy aesthetic. When the user clicks the spinning vinyl, they are redirected to a special song on YouTube.

## ✨ Key Features

*   **Interactive Vinyl Record:** A beautifully animated, spinning vinyl record that serves as the central interactive element.
*   **Retro Aesthetic:** A design inspired by the early 2000s internet, featuring pixelated fonts, grainy textures, and a vibrant neon-on-dark color scheme.
*   **Dynamic Text Effects:** Neon glow and glitch effects on text elements to enhance the retro vibe.
*   **Minimalist & Responsive:** A clean, single-page layout that looks great on all devices, from desktops to mobile phones.
*   **Click-to-Play:** Simple user interaction—clicking the vinyl opens a special song in a new tab.
*   **Performant Animations:** Smooth, CSS-based animations for a fluid user experience.

## 🚀 Technology Stack

This project is built with a modern, high-performance tech stack:

*   **Framework:** [React](https://react.dev/)
*   **Build Tool:** [Vite](https://vitejs.dev/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **UI Components:** [shadcn/ui](https://ui.shadcn.com/)
*   **Animations:** [Framer Motion](https://www.framer.com/motion/)
*   **Icons:** [Lucide React](https://lucide.dev/)
*   **Deployment:** [Cloudflare Workers](https://workers.cloudflare.com/)

## 🏁 Getting Started

Follow these instructions to get a local copy up and running for development and testing purposes.

### Prerequisites

Make sure you have [Bun](https://bun.sh/) installed on your machine. This project uses Bun as the package manager and runtime.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/heartbeat-harmony.git
    cd heartbeat-harmony
    ```

2.  **Install dependencies:**
    ```bash
    bun install
    ```

3.  **Run the development server:**
    ```bash
    bun dev
    ```

The application will be available at `http://localhost:3000` (or the next available port).

## 💻 Development

The core logic and UI for the application are located in `src/pages/HomePage.tsx`.

*   **Customization:** To change the text, colors, or the YouTube link, modify the component in `src/pages/HomePage.tsx`.
*   **Styling:** The visual theme is configured in `tailwind.config.js`. You can adjust fonts, colors, and animation keyframes here.
*   **Components:** Reusable UI components are built using `shadcn/ui` and can be found in `src/components/ui`.

## ☁️ Deployment

This application is optimized for deployment on the Cloudflare network using Wrangler.

1.  **Login to Wrangler:**
    If you haven't already, authenticate Wrangler with your Cloudflare account:
    ```bash
    bunx wrangler login
    ```

2.  **Build the project:**
    This command bundles the application for production.
    ```bash
    bun run build
    ```

3.  **Deploy to Cloudflare:**
    This command deploys your application to a Cloudflare Worker.
    ```bash
    bun run deploy
    ```

Alternatively, you can deploy directly from your GitHub repository with a single click.

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/nisa4114/heartbeat-harmony)

## 📄 License

This project is open-source and available under the MIT License.