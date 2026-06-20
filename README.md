# 🚀 Hero Apps - Frontend

A modern, pixel-perfect frontend application for browsing and discovering applications. Built with a focus on performance, clean UI, and scalable architecture.

## ✨ Features

- **Server-Side Pagination:** Optimized data fetching with precise limit and skip logic for smooth navigation.
- **Dynamic Sorting:** Filter and sort applications seamlessly by Size, Ratings, and Downloads.
- **Real-time Search:** Search functionality integrated with a debounce logic to prevent unnecessary API calls and server overload.
- **Responsive Layout:** A mobile-friendly and pixel-perfect interface.

## 🛠️ Tech Stack

- **Core:** React.js (Vite)
- **Styling:** Tailwind CSS
- **Icons:** React Icons
- **HTTP Client:** Native Fetch API

## ⚙️ Local Setup & Installation

Run the following commands in your terminal to set up and start the project locally:

```bash
# 1. Clone the repository and enter the directory
git clone <repository-url>
cd hero-apps-client

# 2. Install dependencies
npm install

# 3. Create env file and add your backend API URL
echo "VITE_API_URL=http://localhost:5000" > .env.local

# 4. Start the development server
npm run dev
