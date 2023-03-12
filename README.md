# React Complete Beginner Tutorial

To get started with React, please do [Ali Spittel's very beginner-friendly tutorial](https://welearncode.com/beginners-guide-react-2020/).

This video + text walkthrough will guide you in creating your first React project.

Doing this tutorial will show you:

- How to set up a new React project using a tool called `create-react-app`
- Which files you need to edit
- Fundamental React concepts like components, state, and props
- How to run your React application and see it in the browser

🛑 You do NOT need to follow the instructions at the end of the video to create a repo on GitHub or deploy the code.

## How to use this repo with the tutorial

1. Clone this repo and `cd` into it.
2. Do the tutorial work in the directory that contains this repo.
3. Add, commit, and push as you usually do.

## A Note on Different React Versions

Ali is using earlier versions of React and `create-react-app`. The fundamental concepts are still the same, but the syntax has changed slightly. For example, you will notice that the code you see in your `index.js` differs slightly from the code in the tutorial.

The code in your `index.js` should look like this:

```js
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
```

The function of this code is still consistent with what the tutorial describes with the earlier syntax.
