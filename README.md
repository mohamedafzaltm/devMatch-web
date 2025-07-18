# devMatch Web

A modern, Tinder-inspired web application for connecting users, built with React, Vite, and Tailwind CSS. This project demonstrates best practices in UI/UX, state management, and modular architecture.

## Features
- User authentication and profile management
- Swipeable user cards (like/dislike)
- Real-time chat and connections
- Friend requests and premium features
- Responsive, mobile-first design
- Modern UI with Tailwind CSS

## Tech Stack
- **React** (functional components, hooks)
- **Vite** (fast build tool)
- **Tailwind CSS** (utility-first styling)
- **Zustand** (state management)
- **Socket.io** (real-time communication)
- **Jest** & **React Testing Library** (testing)

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/your-username/devMatch-web-main.git
cd devMatch-web-main

# Install dependencies
npm install
# or
yarn install
```

### Running the App
```bash
# Start the development server
npm run dev
# or
yarn dev
```
Visit [http://localhost:5173](http://localhost:5173) to view the app.

### Building for Production
```bash
npm run build
# or
yarn build
```

## Project Structure
```
src/
  components/        # Reusable UI components
  utils/             # State management, constants, sockets
  index.css          # Tailwind CSS imports
  main.jsx           # App entry point
  App.jsx            # Root component
public/              # Static assets
```

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License
[MIT](LICENSE) © Your Name

## Contact
For questions or feedback, please contact [your.email@example.com](mailto:your.email@example.com).
