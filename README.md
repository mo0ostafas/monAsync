# JS Eco-System
onGoing...

> [!CAUTION]
> Use this as **your guide to search about topics**, _not your reference to study topics_.

> [!IMPORTANT]
> Always keep in your mind:
> - what?/how?/why?/use cases for each concept
> - best practices, common mistakes & errors
> - ECMA version, deprecated & browser support
> - Learning never stops .. Keep Updated!

> [!TIP]
> This section is _skippable_, but it's nice to know about:
> - [computer hardware basics](./nice-to-have/hw.md)
> - [different computer science languages categories](./nice-to-have/cs-lang-categories.md)
> - [some OS fundamentals](./nice-to-have/os-fund.md)
> - [some networking fundamentals](./nice-to-have/network-fund.md)
> - [coding & debugging](./nice-to-have/code-debug.md)


## Before you start coding in JS (**IMPORTANT, DON'T SKIP!**)
- What is JS?
- JS History.
- Why JS for web?
- Are there alternatives?
- How does JS code run? (JS under the hood)
  - MIME type (`<script>` tag & file extension)
  - browsers engines (e.g. V8 on chrome, ..)
  - runtime environment (e.g. node.js, deno, ..)
  - CLI (browser console & command-line arguments)
  - event loop, libuv, window, globalThis, this & global

## What are these terms? (_skippable_)
- Functions, First-Class Citizens, HOF, Scope
- Modules, CDN, Packages, Libraries, Frameworks, CSR/SSR
- OOP, DSA, Design Patterns
- Vanilla JS, Scripting Language, JIT Compiler, Console, ASI, DOM
- Static & Dynamic Typing, TS, Memory Management, GC, Hoisting
- Promises, Callbacks, Multi-Threading, Async JS, APIs
- Overwrite/Override

## Syntax
- Comments
- Statements
  - reserved words (keywords)
  - literals
  - operators
  - identifiers
  - references
  - directives
  - decorators

## Comments
- Types
  - inline (`// inline comment`)
  - multi-line/documentation
    ```JS
    /* Multi-line Comment
    ** Tue 04-03-2025 UTC+2 11:33:00 PM
    ** @moOostafas
    */
    ```
- Comments are ued to
  - descripe logic/functionality (maintenance & collaboration)
  - preventing code from running (debugging)
- Real World Projects Comments for Clean Code

## Statements
- Ending Semicolon `;` & Automatic Semicolon Insertion (ASI)
- Line Breaks & White Spaces for Clean Code

## I/O Statements
- `alert()`, `prompt()` & `confirm()` Methods
- `console` Object/API
- DOM & Form Data

## Data Types
- Real World Data Values/Types
- Data Structures Overview
  - Memory Management
  - Data Sizes, Precision & Limits
  - Memory Addresses, Stack & Heap
  - Garbage Collector (GC)
  - Memory Leaks
- Data Values (truthy/falsy, mutable, iterable, configurable, enumerable, writable)
- Data Types, Literals & Object Wrappers
  - `typeof`
  - [7 primitives](./ref/primitives-non-primitives-data-types.md#primitives) (`number`, `string`, `boolean`, `undefined`, `null`, `bigint`, `symbol`)
  - [1 non-primitive](./ref/primitives-non-primitives-data-types.md#non-primitive) (`object`)
    - OOP overview
      - classes & objects
      - prototype (`__proto__`)
      - `this`
      - `constructor` & `super`
      - `instanceof`
    - properties & methods
    - everything is object
      - [6 user-defined](./ref/primitives-non-primitives-data-types.md#user-defined) (array, object, regular expression, function, generator, iterator)
      - class instances & [built-in constructor functions](./ref/primitives-non-primitives-data-types.md#builtin-constructor-functions)
  - [literals/notations](./ref/operators-literals-keywords.md#literals)
  - type coercion/convertion (explicit & implicit)

## Operations
- [Operators](./ref/operators-literals-keywords.md#operators)
- [Built-in Methods](./ref/built-in-properties-methods.md)
- [Precedence](https://www.w3schools.com/js/js_precedence.asp)

## Variables
- Data Storage Concept & Addresses/References
- Declaration Keywords (`var`, `let`, `const`)
- Identifiers Naming Rules & Conventions
- [Assignment Operators](./ref/operators-literals-keywords.md#operators)
- [Data Types](#data-types)
- Intialization, Declaration, Assignment
- Multiple Intialization/Declaration/Asssignment
- Redeclaration, Reassignment
- Lexical Scopes (global, local, block)
- Hoisting & Shadowing
- Accessing Operators
- Logging & Processing
- Override/Overwrite
- 

## FP
- First-Class Citizen
- Declaration/Definition, Invocation/Call, Overloading/Overriding/Overwriting
- Types
  - regular
  - anonymous
  - self-invoked
  - arrow
  - callbacks
  - HOF
  - constructor
  - factory
  - pure & side effects
- Parameters & Arguments
  - pass/call by value & by reference
  - optional/default parameters
  - `argument` array & `...` spread operator
- `return` Type & Void Functions (`undefined`)
- Lexical Scopes (global, local, block)
- Hoisting & Shadowing
- Generators & Iterators
- Closures
- 

## Flow Control
- Synchronous, Asynchronous, Blocking Threads, Multi-Threading
- Flow Control Types
  - accessing data
    - identifier/references
    - index/key/member
    - optional chaning
    - pattern matching (destructuring)
  - descision making
    - boolean expressions & short-circuit evaluations
      - first falsy / last truthy `&&`
      - first truthy / last falsy `||`
      - nullish coalescing (null) `??`
    - selection/conditional statements
      - `if ... else if ... else`
      - ternary `... ? ... : ...`
      - `switch ... case ... default`
  - loops (iterations)
    - `while`, `do ... while`
    - `for`, `for ... in ...`, `for ... of ...`
    - forever
  - jumps (goto)
    - keywords (`continue (<label_name>)`, `break (<label_name>)`)
    - labels (`<label_name>: <loop>`)
  - exception (error) handling
    - `try ... catch ... finally` block
    - `throw` keyword
    - errors
  - functional programming (FP) & modules
  - finite state machine (FSM)
  - asynchronous functions & coroutines
  - event-based (event-driven)
  - promises & meta programming (observables)
  - multitasking (web workers, shared memory)
  - 

## Object Oriented Programming (OOP)
- Classes, `new` Keyword, Instantiation, Objects
- Prototype `__proto__`
- `this` Keyword
- `constuctor` Function & `super`
- [Built-in Constructor Functions](./ref/primitives-non-primitives-data-types.md#builtin-constructor-functions)
- 4 main pillars (inheretance, encapsulation, abstraction, polymorphism)
- 

## Data Structures & Algorithms (DSA)
- [Data Types](#data-types)
- Linked List, Hash Tables, Stacks, Queues, Graphs, Trees
- Searching & Sorting
- Big O Notation
- 

## Design Patterns
- MVC
- 

## Modules
- `require` (Common JS), `import/export` (ES6+)
- Bundling (vite, webpack)
- 

## DOM
- `window` & `document` Objects
- Target Elements
- Events Handling
- Form Validations
- VDOM & Shadow DOM
- 

## BOM
- History & Location
- 

## Web APIs
- Intersection & Resize Observer (effects/animations)
- Local vs Session Storage & Cookies (storage)
- WebSockets vs Server-Sent Events (SSE)
- Streaming (loading instead of waiting)
- WebRTC & Bluetooth (communications)
- WebGL & Canvas (2D/3D graphics)
- Push (push notifications)
- Geolocation (location)
- Drag & Drop
- 

## Async JS
- Callback Hell
- Microtasks & Macrotasks (promises, `setTimeout`, `setInterval`, ..)
- AJAX & XHR (`XMLHttpRequest`)
- Fetch API & 5 HTTP Verbs (`GET`,`POST`,`PUT`,`PATCH`,`DELETE`)
- Cancel ongoing Fetch Requests (`AbortController`)
- Web Socket vs WebRTC
- Service Workers, Background Sync, Web Workers, Caching, Multi-Threading
- Progressive Web Apps (PWAs)
- 

## Node.js
- Client-Side vs Server-Side JS
- Events
- File System `fs`, Encoding/Decoding, Streams, Buffers
- RESTful API Design
- DB Handling (MongoDB, PostegreSQL, Prisma, Redis, Firebase, Appwrite, ORM, ..)
- 

## Security
- `.env`, jwt, salt & pepper
- Authentication/Authorization
- CORS, CSRF, XSS, CSP, ..
- OAuth & OWASP
- 

## Performance & Optimization
- Minification & Compression
- Debouncing & Throttling
- Lazy Loading
- Tree Shaking
- Code Splitting
- Reflow & Repaint
- 

## What to use with JS?
- VSCode & Browser Extensions
- Git/GitHub (version control system/hosting)
- Package Managers (npm, yarn, pnpm, ..)
- jQuery (DOM Manipulation & Animations)
- Floating UI (floating elements positioning)
- Prettier & ESLint (code formatting & linting)
- Flip.js, Luxon, Moment.js & FullCalendar (time/date, counters & event tracking)
- Chart.js (numeric data graphical representation)
- AOS (scroll animations)
- Axios, GraphQL & JSON Web Server (APIs)
- TypeScript (static typing)
- Vite & Webpack (bundling)
- React (JSX, SPAs, reusable components, states, ..)
- React Router (routing)
- Redux (state management)
- Tailwind CSS & Shadcn (components styling) 
- NEXT & Astro (react framework for SSR)
- Node.js, Deno & Bun (JS/TS runtime)
- Nodemon (server refreshing with server-side code changes)
- Nest (progressive node.js framework)
- Express, Postman/HTTPie (APIs, routing, middlewares, ..)
- Appwrite, Firebase, Prisma, Redis, MongoDB, PostegreSQL (DBs)
- JWT & `.env` (security)
- Pug, EJS & MDX (template engines)
- Socket.io (web sockets & PWAs)
- Cypress, Jest & Jasmine (testing)
- React Native & Electron (cross-platforms apps)
- Three.js (3D & graphics)
- Docker & Kubernetes (DevOps)
- Hostinger VPS & AWS (Hosting)
- 

## Important Topics
- JS is Weird
- [ECMAScript](./ref/ecmascript.md)
- TypeScript
- Clean Code
- `this` Keyword
- `use strict` Directive
- `$` & `_` Variables (naming conventions for proffesionals)
- Template String Formatting (white spaces, line breaks & interpolation `${}`)
- Fetch your Local JSON File & CRUD using JSON Web Server
- 

## Advanced Topics
- Web Assembly (WASM)
- Polyfill
- Hydration
- Module Federation
- Serverless Computing
- Headless CMS (Strapi)
- Microservices Architecture
- Isomorphic JS
- Jamstack
- 
