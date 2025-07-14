# Simple React Dashboard with HeadlessUI

A beginner-friendly dashboard built with React, HeadlessUI, and Tailwind CSS.

## What's Included

This simple dashboard includes:

### HeadlessUI Components Used:
- **Menu**: User profile dropdown in the top-right corner
- **Disclosure**: Expandable "Quick Actions" panel 
- **Transition**: Smooth animations for the dropdown and panels

### Dashboard Features:
- **Header**: Clean navigation bar with user profile menu
- **Stats Cards**: Display key metrics (Users, Revenue, Orders, Conversion Rate)
- **Quick Actions**: Expandable panel with action buttons
- **Notifications**: Recent activity feed

## How to Run

1. Make sure you're in the `react-dashboard` directory
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`
4. Open your browser to the URL shown in the terminal (usually http://localhost:5173)

## Understanding the Code

Since you're new to React, here are the key concepts used:

### React Basics:
- **Components**: The dashboard is one big component (`App.jsx`)
- **State**: Used with `useState` to store the stats data
- **Props**: Used to pass data to HeadlessUI components

### HeadlessUI Features:
- **Accessibility**: All components work with keyboard navigation and screen readers
- **Styling Freedom**: HeadlessUI provides behavior, Tailwind provides the styling
- **Smooth Animations**: Built-in transition components for better UX

### File Structure:
```
src/
├── App.jsx          # Main dashboard component
├── index.css        # Tailwind CSS imports
└── main.jsx         # App entry point
```

## Try Interacting With:
1. Click the user icon in the top-right to see the dropdown menu
2. Click "View Analytics" to expand the quick actions panel
3. Hover over the action buttons to see hover effects

## Next Steps for Learning:
1. Try changing the stats data in the `stats` array
2. Add more menu items to the profile dropdown
3. Create separate components for each section
4. Add more HeadlessUI components like Dialog or Tabs

Happy coding! 🚀
