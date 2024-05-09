#Vue.js

1. **What is Vue.js?**
   - Vue.js is a JavaScript framework used mainly for building user interfaces.

2. **What are the key features of Vue.js?**
   - Declarative rendering, component-based architecture, two-way data binding, directives, reactivity.

3. **What is data binding in Vue.js?**
   - Data binding in Vue.js establishes a connection between the UI and the application's data. It ensures that changes in the data are
     reflected in the UI, and vice versa, without manual intervention.

4. **What are Vue components?**
   - Vue components are reusable Vue instances with a defined template, script, and styles.
     They encapsulate functionality and can be composed to build complex UIs.

5. **Explain Vue directives.**
   - Vue directives are special HTML attributes prefixed with `v-`, used to apply reactive behavior to the DOM.
     They enable manipulation of the DOM, conditional rendering, and event handling.

6. **What is Vue Router?**
   - Vue Router is the official routing library for Vue.js. It enables navigation between different views in an application.

7. **How do you iterate in Vue.js? Show an example!**
   - By using the `v-for` directive.
     
  `<ul> <li v-for="(value, key) in user" :key="key">{{ key }}: {{ value }}</li> </ul>`

   The above example creates an unordered list and iterates on the user object, rendering the value of each key and property.
   All rendered elements should have a unique key.
  
8. **What is Vue CLI?**
   - Vue CLI (Command Line Interface) is a command-line tool used for scaffolding Vue.js projects. It provides a standard build setup,
     development server, and other essential features for Vue development.

9. **Explain Vue's reactivity system.**
   - Vue's reactivity system automatically updates the DOM when the underlying data changes. It achieves this by tracking dependencies
     between data properties and re-rendering components when necessary.

10. **How does Vue handle events?**
    - Vue allows you to listen to DOM events using the `v-on` directive or the `@` shorthand. Events can be bound to methods in the Vue
      instance to handle user interactions effectively.
