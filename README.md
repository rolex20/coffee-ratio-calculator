# Coffee Ratio Calculator

Coffee Ratio Calculator is a self-contained web app for building coffee recipes from brew method, drink size, strength ratio, scoop size, roast level, grind size, and brew time. It gives home brewers and coffee enthusiasts an immediate recipe summary with water, coffee, scoop, temperature, grind, and brew-length recommendations.

Built as a dependency-light client-side application with real-time calculation logic, DOM-driven state management, responsive HTML/CSS, semantic form controls, accessible ARIA labels, CSS custom properties, dynamic tables, range sliders, embedded SVG, and Vanilla JavaScript optimized for simple GitHub Pages hosting.

## Live App

The app is designed to run directly from a single HTML file:

```text
https://rolex20.github.io/coffee-ratio-calculator/MyCoffeeCalculator.html
```

## Features

- Choose from common brew methods: Autodrip, Pour Over (v60), Chemex, French Press, AeroPress, Mokapot, Siphon, and Cold Brew.
- Adjust drink size from 8 to 64 ounces with a range slider, stepper buttons, or preset cup sizes.
- Select coffee strength with ratio presets from Ultra Mild 1:34 through Average 1:16, or fine-tune the ratio manually.
- Calculate water in ounces, grams, and milliliters in real time.
- Calculate total ground coffee in grams and approximate scoops for 6 gram or 7 gram scoop sizes.
- Choose light, medium, or dark roast and see the matching water-temperature guidance.
- Highlight the recommended grind size for the selected brew method.
- Select fast, balanced, or robust brew-length suggestions.
- Review the complete recipe in a final summary table.

## Technologies

- Real-time client-side calculation engine
- DOM-driven state management
- Responsive HTML and CSS
- Semantic form controls
- Accessible ARIA labels
- CSS custom properties
- Dynamic table highlighting
- Range sliders and stepper controls
- Embedded SVG icon
- Vanilla JavaScript
- GitHub Pages

## How It Works

The calculator converts the selected drink size into grams and milliliters, then divides the water weight by the selected brew ratio to estimate the required coffee dose.

```text
water grams = ounces * 28.3495
water milliliters = ounces * 29.5735
coffee grams = water grams / brew ratio
scoops = coffee grams / selected scoop size
```

All recipe values update immediately when the user changes brew method, drink size, ratio, scoop size, roast level, or brew length.

## Run Locally

Open `MyCoffeeCalculator.html` in any modern browser. No build step, package manager, backend, or local server is required.

## Repository Topics

Recommended GitHub topics for this project:

`coffee`, `coffee-calculator`, `brew-ratio`, `coffee-ratio`, `barista-tools`, `pourover`, `french-press`, `chemex`, `aeropress`, `cold-brew`, `github-pages`, `javascript`

## SEO Keywords

coffee ratio calculator, coffee to water ratio calculator, coffee water ratio, brew ratio calculator, coffee recipe calculator, coffee brewing calculator, coffee grounds calculator, coffee measurement calculator, coffee scoop calculator, coffee strength calculator, pour over coffee calculator, v60 ratio calculator, Chemex ratio calculator, French press ratio calculator, AeroPress ratio calculator, moka pot ratio calculator, cold brew ratio calculator, siphon coffee calculator, drip coffee ratio, autodrip coffee calculator, home coffee brewing, specialty coffee calculator, barista tools, coffee brewing guide, grind size guide, coffee water temperature, coffee grams calculator, coffee ounces to grams, coffee milliliters calculator, GitHub Pages coffee app, JavaScript coffee calculator

## License

This project is licensed under the MIT License.
