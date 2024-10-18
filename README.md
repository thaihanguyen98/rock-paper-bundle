<h1>Rock, Paper Bundle 🪨 📄 ✂️ </h1>
The "Rock, Paper, Bundle" project is an off-platform web development project focused on configuring an existing web application to utilise Webpack as a build tool. The project involves applying Webpack to a finished web app lacking build tools. Unlike introducing new functionality, the primary focus of this project is changing how various resources are combined within the web application. It aims to configure the project for bundling using Webpack, following steps similar to those covered in the "Building Apps with Webpack" lesson provided by Codecademy. 📦

<h2>Key Steps in the Project:</h2>
<ol>
  <li>Configuring the Node Project:</li>
<ul>
  <li>Initialize the Node project using npm init -y.</li>
  <li>Define build and start commands in the package.json scripts section.</li>
  <li>Install necessary npm packages (as developer dependencies) such as webpack, webpack-cli, webpack-dev-server, style-loader, and css-loader.</li>
</ul>
  <br>
  <li>Configuring Webpack:</li>
  <ul>
    <li>Create a Webpack configuration file (webpack.config.js) and set the mode to development.</li>
    <li>Add rules in the configuration file for handling CSS, fonts (e.g., .woff and .woff2), and images (e.g., .png).</li>
    <li>Define the entry point for the project.</li>
  </ul>
  <br>
  <li>Bundling the CSS:</li>
  <ul>
    <li>Import CSS within the JavaScript code, eliminating the need for a <link> tag in the HTML.</li>
  </ul>
  <br>
  <li>Bundling the JavaScript:</li>
  <ul>
    <li>Use Webpack to manage JavaScript modules by adding import and export statements.</li>
    <li>Replace multiple <script> tags in the HTML with a single <script> tag that embeds the JavaScript code.</li>
  <li>Export functions from specific JavaScript files and import them as needed in the main JavaScript file.</li>
  </ul>
  <br>
  <li>Bundling Images:</li>
  <ul>
  <li>Import image assets (Scissors, Rock, and Paper icons) using the Webpack syntax and replace their URLs with named import values.</li>
  </ul>
  <br>
  <li>Building and Viewing the App:</li>
  <ul>
  <li>Launch the project by running custom commands using npm run build.</li>
<li>Verify the project by building and previewing the application npm run start.</li>
  </ol>
      <br>
In this project, Webpack is introduced to an existing codebase, enabling the bundling of fonts, images, and CSS. It offers an opportunity to understand how to configure and use Webpack in a real-world web application, simplifying the management of resources and improving the overall development workflow.
