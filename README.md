<div align="center">
  <img src="demo.gif" alt="Logo" width="800">
  <br><br>
</div>

# react-circle
> Renders a svg circle + percentage. It just works

# Install 🚀

```
$ yarn add react-circle
```

# Usage ⛏

**Basic** 🙃

ReactCircle is opinionated and comes with default size and colors, just pass the **progress** prop to get them:

```javascript
import Circle from 'react-circle';

<Circle
  progress={35}
/>
```

**Custom** 💅

Optionally, you can pass the following props and customize it as your will

```javascript
import Circle from 'react-circle';

// All avaliable props for customization:
// Details are ordered as:
// <Type>: <Description>
<Circle
  size={150} // Number: Defines the size of the circle.
  lineWidth={14} // Number: Defines the thickness of the circle's stroke. 
  progress={69} // Number: Update to change the progress and percentage.
  progressColor="cornflowerblue"  // String: Color of "progress" portion of circle.
  bgColor="whitesmoke" // String: Color of "empty" portion of circle.
  textColor="hotpink" // String: Color of percentage text color.
  textStyle={{ 
    font: 'bold 5rem Helvetica, Arial, sans-serif' // CSSProperties: Custom styling for percentage.
  }}
  percentSpacing={10} // Number: Adjust spacing of "%" symbol and number.
  showPercentage={true} // Boolean: Show/hide percentage.
  showPercentageSymbol={true} // Boolean: Show/hide only the "%" symbol.
/>
```
