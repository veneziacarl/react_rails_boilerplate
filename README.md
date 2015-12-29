This is a template for Rails projects with React injected in to the asset pipeline.

app/assets/javascripts contains the bundle.js file which is picked up in the asset pipeline.
The `Client` directory holds all component information and `entry.jsx` which is targeted in the webpack config as the entry point.

To use: <br />
`$ git clone git@github.com:veneziacarl/react_rails_boilerplate.git`

Server commands: <br />
in two separate windows in your rails root run <br />
<li>`$ npm start`</li>
<li>`$ rails s`</li>

TODO:
- [ ] add in react transforms for reloading and error catching
