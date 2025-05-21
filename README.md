# Modern Todo List Application
![Screenshot (1)](https://github.com/user-attachments/assets/08acbfcc-a1cd-4ece-b21d-581c95512c7b)

A beautiful, responsive Todo List application built with React and Bootstrap, featuring modern UI design with gradients and smooth animations.

![Todo App Preview](https://via.placeholder.com/800x400?text=Todo+App+Preview)

## Table of Contents
- [Features](#features)
- [T![Screenshot (1)](https://github.com/user-attachments/assets/ba1e43b8-aadc-41a3-8e52-6a89ea493d6b)
echnologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation Guide](#installation-guide)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Customization Guide](#customization-guide)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Features

### Core Functionality
- ✨ Add new todos with a modern input interface
- 📝 Edit existing todos
- ✅ Mark todos as complete/incomplete
- 🗑️ Delete todos
- 💾 Persistent storage (localStorage)

### UI/UX Features
- 🎨 Beautiful gradient backgrounds
- 📱 Fully responsive design
- 🎭 Smooth hover animations
- 🎯 Modern card-based layout
- 🌈 Custom color schemes
- 🔍 Clean and intuitive interface

## Technologies Used

- **Frontend Framework:** React 19
- **Styling:** Bootstrap 5
- **Build Tool:** Vite
- **Package Manager:** npm
- **Development Tools:**
  - ESLint for code quality
  - Modern JavaScript features
  - CSS3 with gradients and animations

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v16.0.0 or higher)
- npm (v7.0.0 or higher)
- Git (for version control)

### Checking Your Environment
```bash
# Check Node.js version
node --version

# Check npm version
npm --version

# Check Git version
git --version
```

## Installation Guide

### Step 1: Clone the Repository
```bash
# Clone the repository
git clone https://github.com/yourusername/todo-app.git

# Navigate to project directory
cd todo-app
```

### Step 2: Install Dependencies
```bash
# Install all required dependencies
npm install
```

### Step 3: Verify Installation
```bash
# Check if all dependencies are installed correctly
npm list --depth=0
```

## Running the Application

### Development Mode
```bash
# Start the development server
npm run dev
```
The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

### Production Build
```bash
# Create a production build
npm run build

# Preview the production build
npm run preview
```

## Project Structure

```
todo-app/
├── src/
│   ├── components/
│   │   ├── Header.jsx        # Application header component
│   │   ├── ToDoList.jsx      # Todo list container component
│   │   └── ToDoItem.jsx      # Individual todo item component
│   ├── App.jsx              # Main application component
│   ├── main.jsx             # Application entry point
│   └── index.css            # Global styles and Bootstrap import
├── public/                  # Static assets
├── index.html              # HTML template
├── package.json            # Project dependencies and scripts
└── README.md              # Project documentation
```

## Customization Guide

### Changing Colors
1. Open `src/index.css`
2. Modify the gradient values:
```css
body {
    background: linear-gradient(135deg, #f0f9ff 0%, #bae6fd 100%);
}
```

### Modifying Components
1. Header: Edit `src/components/Header.jsx`
2. Todo Items: Edit `src/components/ToDoItem.jsx`
3. Todo List: Edit `src/components/ToDoList.jsx`

### Adding New Features
1. Create new components in the `src/components` directory
2. Import and use them in `App.jsx`
3. Add any new styles to `index.css`

## Troubleshooting

### Common Issues and Solutions

1. **Port Already in Use**
   ```bash
   # Kill the process using port 5173
   npx kill-port 5173
   ```

2. **Module Not Found Errors**
   ```bash
   # Clear npm cache
   npm cache clean --force
   
   # Reinstall dependencies
   rm -rf node_modules
   npm install
   ```

3. **Build Errors**
   ```bash
   # Clear build cache
   npm run build -- --force
   ```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Support

If you encounter any issues or have questions:
- Open an issue in the GitHub repository
- Contact the maintainers
- Check the troubleshooting guide above

---

Made with ❤️ by [Your Name]
