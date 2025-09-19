# Simple Calculator Web App

A basic calculator web application built with HTML, CSS, and JavaScript. This project demonstrates fundamental web development concepts including DOM manipulation, event handling, and responsive design.

## Features

- ✅ Basic arithmetic operations (+, -, *, /)
- ✅ Clear functionality
- ✅ Responsive design
- ✅ Clean, modern UI
- ✅ Error handling for division by zero

## Files Structure

```
calculator/
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Clone or download** the calculator files
2. **Open `index.html`** in your web browser
3. **Start calculating!**

## How to Use

1. Click number buttons to input numbers
2. Click operation buttons (+, -, *, /) to select operations
3. Click "=" to calculate the result
4. Click "C" to clear the calculator

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling, flexbox, and responsive design
- **JavaScript**: DOM manipulation and calculator logic

## Code Highlights

### HTML Structure
```html
<div class="calculator">
    <div class="display">
        <input type="text" id="result" readonly>
    </div>
    <div class="buttons">
        <!-- Calculator buttons -->
    </div>
</div>
```

### JavaScript Logic
```javascript
function calculate() {
    try {
        result.value = eval(result.value);
    } catch (error) {
        result.value = 'Error';
    }
}
```

## Future Enhancements

- [ ] Add keyboard support
- [ ] Implement memory functions (M+, M-, MR, MC)
- [ ] Add scientific calculator features
- [ ] Implement history of calculations
- [ ] Add themes and customization options

## Contributing

Feel free to contribute improvements:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is part of the demo-public-repo and follows the same Apache 2.0 license.