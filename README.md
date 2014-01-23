# Volt Progress Bar

This is the world's simplest progress bar for Volt.  The progress bar updates dynamically with a Volt reactive value.

# Use

To get a progress bar, simply put this code in a Volt view.

  <:progress-bar value="{_width}" total="100" />
  
Value must be a reactive value, and total can either be a number or a reactive value.

# Styling

The following css will get included with this component.  Change these classes in your own css file if needed.

```css
  .volt-progress-bar-container{
    overflow:hidden;
    width:100%;
    border:1px solid gray;
  }

  .volt-progress-bar{
    width:0%;
    height:20px;
    background:gray;
  }
```
