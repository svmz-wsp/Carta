# Agent Context: Restaurant Menu Viewer (Internal Tool)

## 🎯 Project Purpose
A lightweight, fast, and simple web application designed for new waiters at a restaurant. It acts as a digital, searchable cheat-sheet for product names and prices. It is NOT for customers.

## 🏗️ Architecture & Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+).
- **Backend/Database:** None (Serverless).
- **Storage:** Browser `LocalStorage` for offline persistence.
- **Hosting:** GitHub Pages.

## 📋 Core Features
1. **Real-time Search:** Waiters must be able to type 2-3 letters and instantly see filtered results.
2. **Read-Only Default State:** The main view must only show the search bar and the list of items to avoid accidental edits during rush hours.
3. **Edit Mode (CRUD):** A secure or hidden toggle to add, modify, or delete items.
4. **Data Portability:** Features to export the menu to a JSON file and import it, allowing the manager to synchronize the menu across multiple waiters' devices without a centralized database.

## 🤖 Agent Rules & Guidelines
- **Simplicity First:** Do not introduce frontend frameworks (React, Vue, Angular) or build tools (Webpack, Vite) unless strictly necessary. Keep dependencies to zero.
- **Mobile-First Design:** The UI must be optimized for portrait mode on smartphones. Use large tap targets and legible fonts.
- **Robust Error Handling:** Ensure `LocalStorage` operations are wrapped in try/catch blocks.
- **Code Style:** Use semantic HTML. Keep CSS modular or well-commented. Write clear, self-documenting JavaScript functions.
- **Language:** Variables and code can be in English, but the User Interface (UI) text MUST be in Spanish (e.g., "Buscar producto...", "Añadir", "Precio").
