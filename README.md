# reactjs-tic-tac-toe

This tic-tac-toe demo application provides a basic but thorough beginner's example of how to interact with the ReactJS 
framework.

The **React Devtools** extension for Chrome and Firefox lets you inspect a React component tree with your browser’s developer tools.
It can be downloaded from [here](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi/related?hl=en).

## Deploy to CloudFoundry

A manifest.yml file is defined at the root of the application, and this file provides metadata related to how to deploy
and provision the application within a Pivotal CloudFoundry environment.

To deploy to CloudFoundry, please use the following command:

```
cd reactjs-tic-tac-toe
cf push
```