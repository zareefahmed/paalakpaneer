### Paalak Paneer



### Installing the `paalakpaneer` Package

#### Step 1: Prerequisites
Ensure you have Node.js and npm installed on your system. You can check their installation by running:
```bash
node -v
npm -v
```
If they are not installed, download and install Node.js (npm comes bundled with it) from [Node.js official website](https://nodejs.org/).

#### Step 2: Create a New Node.js Project
If you're starting a new project, create a new directory and initialize it:
```bash
mkdir my-project
cd my-project
npm init -y
```
This will create a `package.json` file in your project directory.

#### Step 3: Install the `paalakpaneer` Package
Run the following command in your project directory:
```bash
npm install paalakpaneer
```
This command installs the `paalakpaneer` package and adds it as a dependency in your `package.json` file.

### Using the `paalakpaneer` Package

#### Step 1: Require the Package in Your Code
In your project, create a JavaScript file (e.g., `app.js`) and require the `paalakpaneer` package at the top of the file:
```javascript
const paalakpaneer = require('paalakpaneer');
```

#### Step 2: Use the `info` Function
Now, you can use the `info` function from the `paalakpaneer` package:
```javascript
console.log(paalakpaneer.info());
```
This will output: `"This is so good !!!"`

#### Step 3: Run Your Code
Run your JavaScript file using Node.js:
```bash
node app.js
```
You should see the output in the console.

### Complete Example
Here's what your `app.js` might look like:

```javascript
// app.js

const paalakpaneer = require('paalakpaneer');

console.log(paalakpaneer.info()); // Outputs: "This is so good !!!"
```



