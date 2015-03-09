# Vanilla Slider
A simple slider written in pure JS.
It uses CSS transitions for animations.

## Usage

After include the script, call the Slider() passing the selector and the options

```javascript
var mySlider = new Slider('.my-slider', {
  visibles: 3,
  controlNext: '.my-slider-next',
  controlPrev: '.my-slider-prev'
});
```

## Options

These are the current options supported with its default values:

```javascript
var options = {
  
  // Direction, it can be 'horizontal' or 'vertical'
  direction: 'horizontal',
  
  // Items to show
  visibles: 1,
  
  // The elements for the controls.
  // You can pass a 'string' or an DOM element itself
  controlNext: '',
  controlPrev: '',
  
  // Justify the items inside the slider
  justify: true,
  
  // Steps to move with 'next' and 'prev' controls
  steps: 1
  
};
```

