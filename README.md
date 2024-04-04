# debounce-master

debounce functionality npm package

## Installation

Install the package via npm:

```bash
npm install debounce-master



```javascript

import { Debounce } from "debounce-master";

// Define your function
const myFunction = () => {
  // Your function logic here
};

// Create a debounced version of your function with a specified delay
const myDebouncedFunction = Debounce(myFunction, delay);

// Call the debounced function when needed
myDebouncedFunction();
