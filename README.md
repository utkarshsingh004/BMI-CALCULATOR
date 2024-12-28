**# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
**# BMI Calculator

A simple and interactive Body Mass Index (BMI) Calculator built with React and Vite.

## Features
- **Real-Time BMI Calculation**: Input weight and height to instantly calculate BMI.
- **Health Classification**: Provides feedback on BMI categories (underweight, normal, overweight, or obese).
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Unit Conversion**: Supports metric (kg, cm) and imperial (lbs, inches) units.

## Getting Started

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or later)
- npm or [yarn](https://yarnpkg.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/utkarshsingh004/BMI-CALCULATOR.git
   cd bmi-calculator
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open the app in your browser at `http://localhost:5173`.

### Build for Production
To create a production-ready build:
```bash
npm run build
# or
yarn build
```

The build files will be generated in the `dist` directory.

## Project Structure
```
.
├── public         # Static assets
├── src            # Source files
│   ├── components # React components
│   ├── styles     # CSS or SCSS files
│   ├── App.jsx    # Main application component
│   └── main.jsx   # Entry point
├── package.json   # Project metadata and dependencies
├── vite.config.js # Vite configuration
└── README.md      # Project documentation
```

## Usage
1. Input your weight and height in the provided fields.
2. Select the desired unit system (metric or imperial).
3. View your BMI result and corresponding health classification.

## Technologies Used
- **React**: Frontend library for building user interfaces.
- **Vite**: Fast and lightweight development environment.
- **CSS**: For styling the application.

## Future Enhancements
- Add a BMI history tracker.
- Include charts to visualize BMI trends.
- Provide personalized health tips based on BMI.

## Acknowledgments
- Inspired by various online BMI calculators and health tools.
- Built with love using React and Vite.
