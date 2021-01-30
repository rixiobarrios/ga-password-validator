[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# React Password Validator

Recreate a password validator in React. Your final product should function
similarly to [this deployed version](https://password-validator-demo.herokuapp.com/) of the
component.

## Prerequisites

- React
- Components, state, and props

## Instructions

1. Fork and clone this repository into your `sandbox` directory.
1. Change into the new directory with `cd password-validator.
1. Install dependencies with `npm install`.
1. Open the project in VS Code with `code .`.
1. Back in the Terminal type `npm run start` to start your development server.
1. Complete the [requirements](requirements) listed below.
1. Create a pull request when done.

## Requirements

Take the existing markup rendered from the `Validator` component in
[`src/Validator.js`](src/Validator.js) and change into a fully functioning
component. This means that you only have to add functionality - no JSX or
styling - to the existing code.

## Steps

1. Add a constructor method and initialize state. Your state should include
   `username`, `password`, `passwordConfirm`, and `valid` properties.

```jsx
this.state = {
  username: '',
  password: '',
  passwordConfirm: '',
  valid: true
};
```

2. Add a methods for handling each input's onChange event.
3. Add a method to handle the form submission. Remember to prevent the default behavior of a form being submitted.
4. Display a message if the user's inputs are valid or invalid.

## Bonus

For the bonus:

- Add a class of `invalid` or `valid` to the message conditionally (CSS already exists).
- Add a cancel button that clears the fields when clicked. There is a cancel class you can add to the button to make it display red. (hint: make sure it has `type="button"`)
- Update the validation message any time the user types something in the confirmPassword input.
- Make sure passwords are at least 7 characters in length.
- Make sure passwords includes a number and a special character. (Check out
  [Regex](http://emailregex.com/))

## Resources

- [Thinking in React](https://facebook.github.io/react/docs/thinking-in-react.html)
- [Forms in React](https://facebook.github.io/react/docs/forms.html#controlled-components)
- [Components and Props](https://facebook.github.io/react/docs/components-and-props.html)
- [Adding State to a Component](https://facebook.github.io/react/docs/state-and-lifecycle.html#adding-local-state-to-a-class)

## Plagiarism

Take a moment to refamiliarize yourself with the
[Plagiarism policy](https://git.generalassemb.ly/DC-WDI/Administrative/blob/master/plagiarism.md).
Plagiarized work will not be accepted.

## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
# ga-password-validator
