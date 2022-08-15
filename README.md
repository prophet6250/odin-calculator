# odin-calculator
A simple calculator, made for partial fulfilment of The Odin Project curriculum

## Todo:

- [] Basic arithmetic operations working (add, subtract, divide, multiply)
- [] Create a new function `operate` that takes an operator and 2 numbers and then calls one of the above functions on the numbers
- [] Create a basic HTML calculator with buttons for each digit, each of the above functions and an “Equals” key
  - [] There should be a display for the calculator, fill it up with some dummy numbers
  - [] Add clear button 
- [] Create the functions that populate the display when you click the number buttons
- [] Calculator should work by now. User should be able to enter any set of operator, inputs, and it should work just fine
- 
## Gotchas:

- [] Only one pair of operations should be evaluated at a time, in case user enters a complex expression
- [] Round answers up a certain limit, so that they don't overflow the display
- [] Ensure checks are present in case user presses `=` before any inputs
- [] There should be a `clear` button that clears out all of the previous inputs and operator
- [] Handle "divide by zero" gracefully (or disgracefully, doesn't matter; just handle it!)

## Extras

- [] Allow user to do floating point arithmetic
  - [] Have checks in place so that user doesn't do something like `1.2.3 + 4.5.6`
- [] Make it look nice (lol)
- [] Add backspace button to clear out an input
  - [] Make the backspace work digit-by-digit (and not backspace a whole number in one go)
- [] Add keyboard support

