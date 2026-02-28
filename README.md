# Scroll Car Animation

A dynamic scroll-based animation project featuring a car that moves across the screen as you scroll, revealing text and statistics. Built with GSAP and ScrollTrigger for smooth, engaging scroll interactions.

## 🎯 Features

- **Scroll-Driven Animation**: Car moves smoothly across the screen based on scroll position
- **Text Reveal**: Letters appear progressively as the car moves, spelling "WELCOME ITZFIZZ"
- **Statistics Display**: Four text boxes appear at different scroll points showing key metrics:
  - 58% Increase in pick up point use
  - 23% Decrease in customer phone calls
  - 27% Increase in pick up point use
  - 40% Decrease in customer phone calls
- **Visual Trail**: Green trail follows the car's movement
- **Responsive Design**: Adapts to different screen sizes

## 🚀 Live Demo

Visit the live project: [https://assignment-itz-fizz.vercel.app/](https://assignment-itz-fizz.vercel.app/)

## 💻 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox and positioning
- **JavaScript (Vanilla)**: Interactive functionality
- **GSAP 3.12.2**: Animation library for scroll-based effects
- **ScrollTrigger**: GSAP plugin for scroll-triggered animations

## 📁 Project Structure

```
assignment/
├── index.html      # Main HTML structure
├── style.css       # All CSS styling
├── app.js          # JavaScript animations and logic
├── car.png         # Car image asset
└── README.md       # Project documentation
```

## 🛠️ Setup & Installation

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Navigate to the project directory:
```bash
cd assignment
```

3. Open `index.html` in your web browser or serve using a local server:
```bash
python -m http.server 8000
# or use any other local server
```

4. Scroll through the page to see the animation in action!

## 📋 How It Works

1. **Car Movement**: The car element animates from left to right as you scroll down the page
2. **Letter Reveal**: Each letter in "WELCOME ITZFIZZ" becomes visible when the car reaches its position
3. **Text Box Animation**: Four information boxes fade in sequentially at different scroll points
4. **Trail Effect**: A green trail bar grows as the car moves, showing progress

## 🎨 Customization

You can easily customize:
- **Car Width**: Adjust `carWidth` constant in `app.js`
- **Colors**: Modify color values in `style.css`
- **Timing**: Change scroll trigger start/end points in `app.js`
- **Text Content**: Update text in relevant boxes in `index.html`

## 📦 Dependencies

All dependencies are loaded via CDN:
- GSAP: `https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js`
- ScrollTrigger: `https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js`

## 👤 Author

Created as an interactive scroll animation project demonstrating GSAP and ScrollTrigger capabilities.

## 📄 License

This project is open source and available for educational and commercial use.

---

**Enjoy scrolling! 🎬**
