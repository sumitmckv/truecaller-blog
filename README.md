# Truecaller Blog
It contains two directories, **web and server.**

## Web
It contains the client side code written in Vue.js and in Typescript.

Instructions about project setup and deployment can be found [here](web/README.md).

## Server
It contains the server side code written in Express.

It acts as a proxy server between the client and wordpress.com’s REST api.

Instructions about project setup and deployment can be found [here](server/README.md).

## Technology Used
**Web:**

- [Vue.js](https://vuejs.org/) - Web Framework for building user interfaces
- [Typescript](https://www.typescriptlang.org/) - TypeScript extends JavaScript by adding types
- [Vue Router](https://router.vuejs.org/) - Router for Vue.js
- [Vuex](https://vuex.vuejs.org/) - State management library for Vue.js applications
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- [Ky](https://github.com/sindresorhus/ky) -  HTTP client based on the browser Fetch API

**Server:**

- [Express](https://expressjs.com/) - Minimalist web framework for Node.js
- [Typescript](https://www.typescriptlang.org/) - TypeScript extends JavaScript by adding types.
- [Got](https://github.com/sindresorhus/got) - HTTP request library for Node.js

## Future Improvement
- Implement rate limiter, caching in the proxy server.
- Improve page responsiveness so that it looks for more elegant in different resolution.
- Implement server side rendering.
- Improve error handling.

