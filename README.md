# DAWG STRENGTH - Trainer Website

A single-page Next.js application for a fitness trainer/coach website.

## Prerequisites

Before you begin, make sure you have the following installed:

- **Node.js** (version 18 or higher) - [Download here](https://nodejs.org/)
- **Git** - [Download here](https://git-scm.com/)
- **Cursor** (or any code editor) - [Download here](https://cursor.sh/)

## Setup Instructions

### 1. Clone the Repository

Open your terminal and navigate to where you want to store the project, then run:

```bash
git clone <your-github-repo-url>
cd kleincoach
```

Replace `<your-github-repo-url>` with the actual GitHub repository URL.

### 2. Install Dependencies

Install all required packages:

```bash
npm install
```

This will install all dependencies listed in `package.json`, including:
- Next.js 16
- React 19
- Tailwind CSS 4
- TypeScript
- And other required packages

### 3. Open in Cursor

1. Open Cursor
2. Go to **File → Open Folder**
3. Select the `kleincoach` folder you just cloned

### 4. Start the Development Server

In the terminal (you can use Cursor's integrated terminal), run:

```bash
npm run dev
```

The development server will start and you should see output like:
```
  ▲ Next.js 16.0.10
  - Local:        http://localhost:3000
```

### 5. View the Website

Open your browser and navigate to:
```
http://localhost:3000
```

You should now see the website running locally!

## Project Structure

- `app/page.tsx` - Main page with all sections (Hero, About, Services, Client Stories, Contact, Quote)
- `components/` - All React components
- `components/ui/` - Reusable UI components (Button, Card, Carousel, etc.)
- `app/globals.css` - Global styles and Tailwind configuration

## Available Scripts

- `npm run dev` - Start development server (http://localhost:3000)
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Notes

- This is a **single-page application** - all sections are on one page
- The carousel component uses Embla Carousel for client stories
- Navigation uses smooth scrolling to anchor links
- The project uses Tailwind CSS 4 for styling

## Troubleshooting

**Port 3000 already in use?**
- Kill the process using port 3000, or run: `npm run dev -- -p 3001`

**Dependencies not installing?**
- Make sure you have Node.js 18+ installed
- Try deleting `node_modules` and `package-lock.json`, then run `npm install` again

**TypeScript errors?**
- Make sure all dependencies are installed: `npm install`
- Restart your TypeScript server in Cursor (Cmd/Ctrl + Shift + P → "TypeScript: Restart TS Server")
