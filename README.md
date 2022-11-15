# How to create a Chrome extension for GPT-3 questions with ReactJS

![Cover](https://d2pwmb8xsybju4.cloudfront.net/posts/gpt3-chrome-extansion/linkedin_card.png "Cover")
I'm a big fan of using the OpenAI **Playground**, and I have numerous saved templates for generating landing page headlines and checking my grammar. In this walkthrough, we'll build a Chrome extension so you don't have to leave your browser to ask GPT-3 questions.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and all available scripts are shown at the end.

---

## Disclaimer
Do not publish an app or an extension with any of your API keys; this tutorial is just a walkthrough of creating a Chrome extension. Don't expose unencrypted API keys/secrets/credentials if you're planning to publish an app or an extension.

---

## Outline
**1. Create a ReactJS app**<br>
**2. Create extension updates**<br>
**3. Install Material UI** (optional)<br>
**4. Create the extension UI**<br>
**5. Get OpenAI API key**<br>
**6. Add OpenAI configuration**<br>
**7. Create GPT-3 completion**<br>
**8. Add favicon**<br>
**9. Upload extension**<br>
**10. UI fixes**<br>
**11. Save the state** (optional)<br>
**12. Ask away**<br>


## Prerequisites:
**- Node**<br>
**- npm**

## Detailed walkthrough
Read blog post for a detailed walkthrough: https://norahsakal.com/blog/create-gpt3-chrome-extension

---

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
