# MERN Stack Interview Questions & Answers

> Click ⭐ if you like the project. Follow me [@sisi_tarakk](https://www.instagram.com/sisi_tarakk) on Instagram and [@sisitarak](https://www.linkedin.com/in/sisitarak) on LinkedIn for more.

---

> Pull Requests are highly recommended and appreciated. 🙌

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

#### 🟢 Basic Level — MERN Overview & JavaScript Fundamentals

| No. | Questions |
| --- | --------- |
| 1 | [What is the MERN Stack?](#1-what-is-the-mern-stack) |
| 2 | [Why is the MERN Stack popular? What are its advantages?](#2-why-is-the-mern-stack-popular-what-are-its-advantages) |
| 3 | [How does data flow in a MERN application?](#3-how-does-data-flow-in-a-mern-application) |
| 4 | [What is the difference between SQL and NoSQL databases?](#4-what-is-the-difference-between-sql-and-nosql-databases) |
| 5 | [What is npm? Why is it important in MERN development?](#5-what-is-npm-why-is-it-important-in-mern-development) |
| 6 | [What is a REST API? How does it work in MERN?](#6-what-is-a-rest-api-how-does-it-work-in-mern) |
| 7 | [What is CORS? Why is it needed in MERN apps?](#7-what-is-cors-why-is-it-needed-in-mern-apps) |
| 8 | [What is JSON? How is it used in MERN?](#8-what-is-json-how-is-it-used-in-mern) |
| 9 | [What is the difference between synchronous and asynchronous programming?](#9-what-is-the-difference-between-synchronous-and-asynchronous-programming) |
| 10 | [What are Promises in JavaScript?](#10-what-are-promises-in-javascript) |
| 11 | [What is async/await in JavaScript?](#11-what-is-asyncawait-in-javascript) |
| 12 | [What is callback hell and how do you avoid it?](#12-what-is-callback-hell-and-how-do-you-avoid-it) |
| 13 | [What is the difference between var, let, and const?](#13-what-is-the-difference-between-var-let-and-const) |
| 14 | [What are closures in JavaScript?](#14-what-are-closures-in-javascript) |
| 15 | [What is the Event Loop in JavaScript?](#15-what-is-the-event-loop-in-javascript) |

#### 🟢 Basic Level — MongoDB

| No. | Questions |
| --- | --------- |
| 16 | [What is MongoDB?](#16-what-is-mongodb) |
| 17 | [What is BSON? How is it different from JSON?](#17-what-is-bson-how-is-it-different-from-json) |
| 18 | [What are collections and documents in MongoDB?](#18-what-are-collections-and-documents-in-mongodb) |
| 19 | [What is Mongoose? Why is it used with MongoDB?](#19-what-is-mongoose-why-is-it-used-with-mongodb) |
| 20 | [What are Mongoose Schemas and Models?](#20-what-are-mongoose-schemas-and-models) |
| 21 | [What are the basic CRUD operations in MongoDB?](#21-what-are-the-basic-crud-operations-in-mongodb) |
| 22 | [What are indexes in MongoDB? Why are they important?](#22-what-are-indexes-in-mongodb-why-are-they-important) |

#### 🟢 Basic Level — Node.js

| No. | Questions |
| --- | --------- |
| 23 | [What is Node.js? Why is it used in MERN?](#23-what-is-nodejs-why-is-it-used-in-mern) |
| 24 | [What is the difference between Node.js and a browser JavaScript engine?](#24-what-is-the-difference-between-nodejs-and-a-browser-javascript-engine) |
| 25 | [What are Node.js modules? What is require vs import?](#25-what-are-nodejs-modules-what-is-require-vs-import) |

#### 🟢 Basic Level — Express.js

| No. | Questions |
| --- | --------- |
| 26 | [What is Express.js? Why is it used in MERN?](#26-what-is-expressjs-why-is-it-used-in-mern) |
| 27 | [How do you create a basic Express server?](#27-how-do-you-create-a-basic-express-server) |
| 28 | [What is middleware in Express.js?](#28-what-is-middleware-in-expressjs) |
| 29 | [What are the HTTP methods and how are they used in Express routing?](#29-what-are-the-http-methods-and-how-are-they-used-in-express-routing) |
| 30 | [What is the difference between req.params, req.query, and req.body?](#30-what-is-the-difference-between-reqparams-reqquery-and-reqbody) |

#### 🟡 Medium Level — MongoDB Deep Dive

| No. | Questions |
| --- | --------- |
| 31 | [What is the MongoDB Aggregation Pipeline?](#31-what-is-the-mongodb-aggregation-pipeline) |
| 32 | [How does MongoDB handle relationships? What are embedding vs referencing strategies?](#32-how-does-mongodb-handle-relationships-what-are-embedding-vs-referencing-strategies) |
| 33 | [What is population in Mongoose?](#33-what-is-population-in-mongoose) |
| 34 | [What are MongoDB transactions?](#34-what-are-mongodb-transactions) |
| 35 | [What is sharding in MongoDB?](#35-what-is-sharding-in-mongodb) |
| 36 | [What is replication in MongoDB?](#36-what-is-replication-in-mongodb) |
| 37 | [How do you validate data in Mongoose?](#37-how-do-you-validate-data-in-mongoose) |

#### 🟡 Medium Level — Node.js Deep Dive

| No. | Questions |
| --- | --------- |
| 38 | [What is the Node.js Event Loop in depth?](#38-what-is-the-nodejs-event-loop-in-depth) |
| 39 | [What is non-blocking I/O in Node.js?](#39-what-is-non-blocking-io-in-nodejs) |
| 40 | [What is the difference between process.nextTick(), setImmediate(), and setTimeout()?](#40-what-is-the-difference-between-processnexttick-setimmediate-and-settimeout) |
| 41 | [What are Node.js streams?](#41-what-are-nodejs-streams) |
| 42 | [What is clustering in Node.js?](#42-what-is-clustering-in-nodejs) |
| 43 | [What is the difference between spawn, exec, and fork in Node.js?](#43-what-is-the-difference-between-spawn-exec-and-fork-in-nodejs) |
| 44 | [What are environment variables and how do you use them in Node.js?](#44-what-are-environment-variables-and-how-do-you-use-them-in-nodejs) |

#### 🟡 Medium Level — Express.js Deep Dive

| No. | Questions |
| --- | --------- |
| 45 | [What are the types of middleware in Express.js?](#45-what-are-the-types-of-middleware-in-expressjs) |
| 46 | [How do you handle errors in Express.js?](#46-how-do-you-handle-errors-in-expressjs) |
| 47 | [What is Express Router and why is it used?](#47-what-is-express-router-and-why-is-it-used) |
| 48 | [How do you serve static files in Express.js?](#48-how-do-you-serve-static-files-in-expressjs) |
| 49 | [What is the difference between app.use() and app.get()?](#49-what-is-the-difference-between-appuse-and-appget) |
| 50 | [How do you implement rate limiting in Express.js?](#50-how-do-you-implement-rate-limiting-in-expressjs) |

#### 🟡 Medium Level — Authentication & Security

| No. | Questions |
| --- | --------- |
| 51 | [What is JWT (JSON Web Token)? How does it work?](#51-what-is-jwt-json-web-token-how-does-it-work) |
| 52 | [How do you implement authentication in a MERN app?](#52-how-do-you-implement-authentication-in-a-mern-app) |
| 53 | [What is the difference between authentication and authorization?](#53-what-is-the-difference-between-authentication-and-authorization) |
| 54 | [What is bcrypt and why is it used?](#54-what-is-bcrypt-and-why-is-it-used) |
| 55 | [What is an HTTP-only cookie? Why is it more secure than localStorage for JWT?](#55-what-is-an-http-only-cookie-why-is-it-more-secure-than-localstorage-for-jwt) |
| 56 | [What is OAuth 2.0? How is it used in MERN apps?](#56-what-is-oauth-20-how-is-it-used-in-mern-apps) |
| 57 | [How do you protect routes in a MERN application?](#57-how-do-you-protect-routes-in-a-mern-application) |

#### 🟡 Medium Level — Full Stack Integration

| No. | Questions |
| --- | --------- |
| 58 | [How does the React frontend communicate with the Express backend?](#58-how-does-the-react-frontend-communicate-with-the-express-backend) |
| 59 | [What is Axios? How is it different from the fetch API?](#59-what-is-axios-how-is-it-different-from-the-fetch-api) |
| 60 | [How do you connect MongoDB to an Express app using Mongoose?](#60-how-do-you-connect-mongodb-to-an-express-app-using-mongoose) |
| 61 | [What is a proxy in a MERN app development setup?](#61-what-is-a-proxy-in-a-mern-app-development-setup) |
| 62 | [What is WebSocket? When would you use it instead of REST in MERN?](#62-what-is-websocket-when-would-you-use-it-instead-of-rest-in-mern) |
| 63 | [How do you handle file uploads in a MERN application?](#63-how-do-you-handle-file-uploads-in-a-mern-application) |
| 64 | [What is pagination and how do you implement it in MERN?](#64-what-is-pagination-and-how-do-you-implement-it-in-mern) |

#### 🔴 Advanced Level — Architecture & Performance

| No. | Questions |
| --- | --------- |
| 65 | [What is MVC architecture? How does it apply to MERN?](#65-what-is-mvc-architecture-how-does-it-apply-to-mern) |
| 66 | [How do you structure a large MERN project?](#66-how-do-you-structure-a-large-mern-project) |
| 67 | [What is caching and how do you implement it in a MERN app?](#67-what-is-caching-and-how-do-you-implement-it-in-a-mern-app) |
| 68 | [What is Redis and how is it used with MERN?](#68-what-is-redis-and-how-is-it-used-with-mern) |
| 69 | [How do you optimize MongoDB query performance?](#69-how-do-you-optimize-mongodb-query-performance) |
| 70 | [What is the N+1 query problem and how do you fix it in Mongoose?](#70-what-is-the-n1-query-problem-and-how-do-you-fix-it-in-mongoose) |
| 71 | [How do you handle large file storage in MERN? What is GridFS?](#71-how-do-you-handle-large-file-storage-in-mern-what-is-gridfs) |
| 72 | [What is GraphQL? When would you use it instead of REST in MERN?](#72-what-is-graphql-when-would-you-use-it-instead-of-rest-in-mern) |

#### 🔴 Advanced Level — DevOps & Deployment

| No. | Questions |
| --- | --------- |
| 73 | [How do you deploy a MERN application?](#73-how-do-you-deploy-a-mern-application) |
| 74 | [What is Docker and how is it used in MERN deployment?](#74-what-is-docker-and-how-is-it-used-in-mern-deployment) |
| 75 | [What is CI/CD? How do you set it up for a MERN project?](#75-what-is-cicd-how-do-you-set-it-up-for-a-mern-project) |
| 76 | [What is NGINX and why is it used with MERN apps?](#76-what-is-nginx-and-why-is-it-used-with-mern-apps) |
| 77 | [How do you scale a MERN application?](#77-how-do-you-scale-a-mern-application) |

#### 🔴 Advanced Level — Testing & Security

| No. | Questions |
| --- | --------- |
| 78 | [How do you test a MERN application?](#78-how-do-you-test-a-mern-application) |
| 79 | [How do you write unit tests for an Express API?](#79-how-do-you-write-unit-tests-for-an-express-api) |
| 80 | [What are common security vulnerabilities in MERN apps and how do you prevent them?](#80-what-are-common-security-vulnerabilities-in-mern-apps-and-how-do-you-prevent-them) |
| 81 | [What is Helmet.js and why is it used?](#81-what-is-helmetjs-and-why-is-it-used) |
| 82 | [What is input sanitization and how do you implement it?](#82-what-is-input-sanitization-and-how-do-you-implement-it) |

#### 🎯 Scenario & Conceptual Questions (MNC Favourites)

| No. | Questions |
| --- | --------- |
| 83 | [How would you design a real-time chat application using MERN?](#83-how-would-you-design-a-real-time-chat-application-using-mern) |
| 84 | [How would you implement role-based access control (RBAC) in MERN?](#84-how-would-you-implement-role-based-access-control-rbac-in-mern) |
| 85 | [How do you handle API versioning in Express.js?](#85-how-do-you-handle-api-versioning-in-expressjs) |
| 86 | [How would you implement a search feature in a MERN app?](#86-how-would-you-implement-a-search-feature-in-a-mern-app) |
| 87 | [What is SSR and when would you use it in a MERN app?](#87-what-is-ssr-and-when-would-you-use-it-in-a-mern-app) |
| 88 | [How do you handle errors globally in a MERN application?](#88-how-do-you-handle-errors-globally-in-a-mern-application) |
| 89 | [How would you implement refresh token rotation in a MERN app?](#89-how-would-you-implement-refresh-token-rotation-in-a-mern-app) |
| 90 | [What is microservices architecture? How does it differ from monolithic MERN?](#90-what-is-microservices-architecture-how-does-it-differ-from-monolithic-mern) |
| 91 | [How do you implement email verification in a MERN app?](#91-how-do-you-implement-email-verification-in-a-mern-app) |
| 92 | [How would you implement infinite scroll in a MERN app?](#92-how-would-you-implement-infinite-scroll-in-a-mern-app) |
| 93 | [What is the difference between monorepo and polyrepo in a MERN project?](#93-what-is-the-difference-between-monorepo-and-polyrepo-in-a-mern-project) |
| 94 | [How do you manage API keys and secrets securely in MERN?](#94-how-do-you-manage-api-keys-and-secrets-securely-in-mern) |
| 95 | [What is the difference between horizontal and vertical scaling in MERN?](#95-what-is-the-difference-between-horizontal-and-vertical-scaling-in-mern) |
| 96 | [How would you implement a notification system in a MERN app?](#96-how-would-you-implement-a-notification-system-in-a-mern-app) |
| 97 | [How do you handle CORS errors in a MERN app?](#97-how-do-you-handle-cors-errors-in-a-mern-app) |
| 98 | [What is the difference between PUT and PATCH in REST APIs?](#98-what-is-the-difference-between-put-and-patch-in-rest-apis) |
| 99 | [How would you implement soft delete in MongoDB?](#99-how-would-you-implement-soft-delete-in-mongodb) |
| 100 | [What are the latest trends in MERN stack development (2024–2025)?](#100-what-are-the-latest-trends-in-mern-stack-development-20242025) |

</details>

---

<br>

## 🟢 Basic Level — MERN Overview & JavaScript Fundamentals

<br>

### 1. What is the MERN Stack?

MERN Stack is a collection of **four JavaScript technologies** used together to build full-stack web applications — from database to server to client UI — entirely in JavaScript.

| Letter | Technology | Role |
| ------ | ---------- | ---- |
| **M** | MongoDB | NoSQL Database — stores app data as JSON-like documents |
| **E** | Express.js | Backend framework — handles server logic, routing, middleware |
| **R** | React.js | Frontend library — builds interactive user interfaces |
| **N** | Node.js | Runtime environment — executes JavaScript on the server |

```
Browser (React)
     ↕  HTTP Requests / Responses
Express.js Server (Node.js)
     ↕  Mongoose Queries
MongoDB Database
```

> The biggest advantage: **JavaScript everywhere** — one language for frontend, backend, and database queries.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 2. Why is the MERN Stack popular? What are its advantages?

| Advantage | Description |
| --------- | ----------- |
| **JavaScript everywhere** | One language across the entire stack — less context switching |
| **JSON data flow** | Data flows as JSON from MongoDB → Express → React seamlessly |
| **Open source** | All four technologies are free and community-driven |
| **High performance** | Node.js non-blocking I/O + React Virtual DOM = fast apps |
| **Scalability** | Each layer can be scaled independently |
| **Large ecosystem** | Huge npm registry, active communities, abundant resources |
| **Industry demand** | Used by Facebook, Netflix, Airbnb, Uber, LinkedIn |

**Comparison with other stacks:**

| Stack | Languages | DB |
| ----- | --------- | -- |
| MERN | JavaScript | MongoDB |
| MEAN | JavaScript | MongoDB (Angular instead of React) |
| LAMP | PHP + JavaScript | MySQL |
| Django | Python + JavaScript | PostgreSQL |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 3. How does data flow in a MERN application?

```
User interacts with React UI
         ↓
React sends HTTP request (via Axios/fetch) to Express API
         ↓
Express middleware processes request (auth check, validation, logging)
         ↓
Express route handler calls Mongoose model method
         ↓
Mongoose queries MongoDB
         ↓
MongoDB returns data → Mongoose returns JS object → Express sends JSON response
         ↓
React receives JSON → updates state → re-renders UI
```

**Example flow — user creates a post:**
1. User fills form in React → clicks "Submit"
2. React sends `POST /api/posts` with post data in body
3. Express validates the request, checks JWT auth
4. Mongoose `Post.create(data)` saves to MongoDB
5. Express returns `{ success: true, post: {...} }`
6. React updates posts list in state → new post appears in UI

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 4. What is the difference between SQL and NoSQL databases?

| Feature | SQL (Relational) | NoSQL (MongoDB) |
| ------- | ---------------- | --------------- |
| Data structure | Tables with rows and columns | Documents (JSON/BSON), key-value, graphs |
| Schema | Fixed — defined before inserting data | Flexible — each document can have different fields |
| Relationships | Foreign keys, JOINs | Embedding or referencing |
| Scaling | Vertical (bigger server) | Horizontal (more servers/sharding) |
| ACID compliance | ✅ Full | ✅ Partial (MongoDB 4+ supports multi-doc transactions) |
| Best for | Complex queries, transactions, structured data | Unstructured data, rapid development, large scale |
| Examples | MySQL, PostgreSQL, SQLite | MongoDB, Cassandra, Redis |

```javascript
// SQL — structured table
// users: | id | name | email |
//        | 1  | Sisi | s@s.com |

// MongoDB — flexible document
{
  _id: ObjectId("..."),
  name: "Sisi",
  email: "s@s.com",
  skills: ["React", "Node"],   // arrays allowed
  address: { city: "Tirupati" } // nested objects allowed
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 5. What is npm? Why is it important in MERN development?

npm (Node Package Manager) is the **default package manager for Node.js**. It allows you to install, manage, and publish JavaScript packages.

```bash
# Initialize a new Node.js project
npm init -y

# Install a package (saves to dependencies)
npm install express mongoose axios

# Install as dev dependency (not needed in production)
npm install --save-dev nodemon jest

# Run scripts defined in package.json
npm run start
npm run dev

# Check for security vulnerabilities
npm audit
npm audit fix
```

**Key files:**
- `package.json` — project metadata, dependencies, scripts
- `package-lock.json` — exact versions of all installed packages (commit this to git)
- `node_modules/` — installed packages (add to `.gitignore`)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 6. What is a REST API? How does it work in MERN?

REST (Representational State Transfer) is an **architectural style** for designing APIs using HTTP methods. In MERN, Express.js builds the REST API that React consumes.

**REST principles:**
- **Stateless** — each request contains all info needed
- **Client-Server** — frontend and backend are separate
- **Uniform Interface** — standard HTTP verbs and status codes
- **Resource-based** — everything is a resource with a URL

```javascript
// Express REST API example — User resource
// GET    /api/users       → Get all users
// GET    /api/users/:id   → Get one user
// POST   /api/users       → Create user
// PUT    /api/users/:id   → Update user (full replace)
// PATCH  /api/users/:id   → Update user (partial)
// DELETE /api/users/:id   → Delete user

// HTTP Status codes used in REST:
// 200 OK, 201 Created, 400 Bad Request,
// 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Server Error
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 7. What is CORS? Why is it needed in MERN apps?

CORS (Cross-Origin Resource Sharing) is a **browser security mechanism** that restricts HTTP requests made from one origin (domain/port) to a different origin.

**Why it's needed in MERN:** In development, React runs on `localhost:3000` and Express runs on `localhost:5000` — different ports = different origins → browser blocks the request.

```javascript
// Fix using the cors npm package in Express
const express = require('express');
const cors = require('cors');
const app = express();

// Allow all origins (dev only — not for production)
app.use(cors());

// Allow specific origins (production)
app.use(cors({
  origin: ['https://yourapp.com', 'https://www.yourapp.com'],
  methods: ['GET', 'POST', 'PUT', 'DELETE', 'PATCH'],
  allowedHeaders: ['Content-Type', 'Authorization'],
  credentials: true // allow cookies to be sent cross-origin
}));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 8. What is JSON? How is it used in MERN?

JSON (JavaScript Object Notation) is a **lightweight, text-based data format** for storing and transmitting data. In MERN, JSON is the universal data exchange format across all layers.

```javascript
// JSON structure
{
  "name": "Sisi",
  "age": 20,
  "skills": ["React", "Node.js", "MongoDB"],
  "company": {
    "name": "Webortex",
    "role": "CEO"
  },
  "active": true
}

// In Express: parse incoming JSON body
app.use(express.json()); // parses JSON request bodies

// In React: fetch and parse JSON from API
const response = await fetch('/api/user');
const user = await response.json(); // parse JSON string → JS object

// Stringify JS object → JSON string for storage/transmission
const jsonString = JSON.stringify(user);
const jsObject = JSON.parse(jsonString);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 9. What is the difference between synchronous and asynchronous programming?

| Feature | Synchronous | Asynchronous |
| ------- | ----------- | ------------ |
| Execution | One task at a time, in order | Tasks can run in the background |
| Blocking | ✅ Blocks next operation | ❌ Non-blocking |
| Use case | Simple sequential logic | I/O operations (API calls, DB queries, file reads) |

```javascript
// Synchronous — blocks until done
const data = fs.readFileSync('file.txt', 'utf8'); // blocks everything
console.log(data);
console.log('This runs after file read');

// Asynchronous — non-blocking
fs.readFile('file.txt', 'utf8', (err, data) => {
  console.log(data); // runs when file is ready
});
console.log('This runs IMMEDIATELY, before file read completes');
```

> Node.js is designed around **asynchronous non-blocking I/O** — it can handle thousands of concurrent requests without waiting.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 10. What are Promises in JavaScript?

A Promise is an object representing the **eventual completion or failure** of an asynchronous operation. It has three states: **pending**, **fulfilled**, or **rejected**.

```javascript
// Creating a Promise
const fetchUser = (id) => {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      if (id > 0) resolve({ id, name: 'Sisi' }); // success
      else reject(new Error('Invalid ID'));        // failure
    }, 1000);
  });
};

// Consuming with .then() / .catch()
fetchUser(1)
  .then(user => console.log('User:', user))
  .catch(err => console.error('Error:', err))
  .finally(() => console.log('Done')); // runs regardless

// Promise.all — run multiple promises concurrently
const [users, posts] = await Promise.all([
  fetch('/api/users').then(r => r.json()),
  fetch('/api/posts').then(r => r.json())
]);

// Promise.allSettled — get results even if some fail
const results = await Promise.allSettled([p1, p2, p3]);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 11. What is async/await in JavaScript?

`async/await` is **syntactic sugar over Promises** that makes asynchronous code look and read like synchronous code.

```javascript
// Without async/await (Promise chaining)
function getUser(id) {
  return fetch(`/api/users/${id}`)
    .then(res => res.json())
    .then(user => {
      return fetch(`/api/posts?userId=${user.id}`);
    })
    .then(res => res.json())
    .catch(err => console.error(err));
}

// With async/await — much cleaner
async function getUser(id) {
  try {
    const res = await fetch(`/api/users/${id}`);
    const user = await res.json();

    const postsRes = await fetch(`/api/posts?userId=${user.id}`);
    const posts = await postsRes.json();

    return { user, posts };
  } catch (error) {
    console.error('Error fetching user:', error);
    throw error;
  }
}

// Express route with async/await
app.get('/api/users/:id', async (req, res) => {
  try {
    const user = await User.findById(req.params.id);
    if (!user) return res.status(404).json({ message: 'User not found' });
    res.json(user);
  } catch (error) {
    res.status(500).json({ message: 'Server error' });
  }
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 12. What is callback hell and how do you avoid it?

Callback hell (also called "pyramid of doom") is **deeply nested callbacks** that make code hard to read, debug, and maintain.

```javascript
// ❌ Callback hell
getUser(userId, function(err, user) {
  if (err) handleError(err);
  else getPosts(user.id, function(err, posts) {
    if (err) handleError(err);
    else getComments(posts[0].id, function(err, comments) {
      if (err) handleError(err);
      else {
        // finally do something...
      }
    });
  });
});

// ✅ Solution 1: Promises
getUser(userId)
  .then(user => getPosts(user.id))
  .then(posts => getComments(posts[0].id))
  .then(comments => { /* use comments */ })
  .catch(handleError);

// ✅ Solution 2: async/await (best)
async function getData(userId) {
  try {
    const user = await getUser(userId);
    const posts = await getPosts(user.id);
    const comments = await getComments(posts[0].id);
    return comments;
  } catch (err) {
    handleError(err);
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 13. What is the difference between var, let, and const?

| Feature | `var` | `let` | `const` |
| ------- | ----- | ----- | ------- |
| Scope | Function-scoped | Block-scoped | Block-scoped |
| Re-declaration | ✅ Allowed | ❌ Not allowed | ❌ Not allowed |
| Re-assignment | ✅ Allowed | ✅ Allowed | ❌ Not allowed |
| Hoisting | Hoisted (undefined) | Hoisted (TDZ error) | Hoisted (TDZ error) |
| Use in modern JS | ❌ Avoid | ✅ For mutable | ✅ For constants |

```javascript
// var — function scoped (old, avoid)
function example() {
  if (true) { var x = 1; }
  console.log(x); // 1 — accessible outside the if block!
}

// let — block scoped (use for mutable values)
function example() {
  if (true) { let y = 1; }
  console.log(y); // ReferenceError — y is block scoped
}

// const — block scoped, can't reassign (use by default)
const API_URL = 'https://api.example.com';
// API_URL = 'other'; // TypeError

// Note: const object properties CAN be mutated
const user = { name: 'Sisi' };
user.name = 'Updated'; // ✅ allowed — object reference unchanged
user = {};             // ❌ TypeError — can't reassign the binding
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 14. What are closures in JavaScript?

A closure is a function that **remembers and has access to variables from its outer (lexical) scope**, even after the outer function has finished executing.

```javascript
// Basic closure
function makeCounter(start = 0) {
  let count = start; // outer variable — "closed over"

  return {
    increment: () => ++count,
    decrement: () => --count,
    getCount: () => count
  };
}

const counter = makeCounter(10);
console.log(counter.increment()); // 11
console.log(counter.increment()); // 12
console.log(counter.getCount());  // 12
// `count` is private — only accessible through these methods

// Real-world use in MERN — middleware factory
function requireRole(role) {
  return function(req, res, next) { // closes over `role`
    if (req.user.role !== role) {
      return res.status(403).json({ message: 'Forbidden' });
    }
    next();
  };
}

app.delete('/api/users/:id', requireRole('admin'), deleteUser);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 15. What is the Event Loop in JavaScript?

The Event Loop is the mechanism that allows JavaScript (single-threaded) to perform **non-blocking asynchronous operations** by offloading tasks to the browser/Node.js runtime and processing their callbacks when the call stack is empty.

```
Call Stack (synchronous JS)
      ↕
Web APIs / Node.js APIs (timers, I/O, network)
      ↕
Callback Queue / Task Queue (macrotasks: setTimeout, setInterval)
      ↕
Microtask Queue (Promises, process.nextTick — higher priority)
      ↕
Event Loop (checks: "is call stack empty? → move microtasks first, then tasks")
```

```javascript
console.log('1 — Start');           // Call Stack — runs first

setTimeout(() => {
  console.log('4 — setTimeout');    // Macro task queue — runs last
}, 0);

Promise.resolve()
  .then(() => console.log('3 — Promise')); // Microtask queue — runs before macrotasks

console.log('2 — End');             // Call Stack — runs second

// Output order: 1, 2, 3, 4
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — MongoDB

<br>

### 16. What is MongoDB?

MongoDB is an **open-source, document-oriented NoSQL database** designed for high performance, high availability, and easy scalability. It stores data in flexible, JSON-like documents called **BSON** (Binary JSON).

**Key features:**
- **Flexible schema** — documents in the same collection can have different fields
- **Horizontal scaling** — supports sharding across multiple servers
- **Rich query language** — supports filtering, sorting, aggregation, geospatial queries
- **Indexing** — supports multiple index types for fast queries
- **Native JavaScript** — uses JavaScript for queries and aggregations

```javascript
// Document example — more natural than a relational table
{
  _id: ObjectId("64a1b2c3d4e5f6g7h8i9j0k1"),
  name: "Sisi",
  age: 20,
  skills: ["React", "Node.js", "MongoDB"],
  company: {
    name: "Webortex",
    role: "CEO",
    since: 2023
  },
  createdAt: ISODate("2024-01-15T10:00:00Z")
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 17. What is BSON? How is it different from JSON?

BSON (Binary JSON) is the **binary-encoded serialization format** MongoDB uses to store documents internally.

| Feature | JSON | BSON |
| ------- | ---- | ---- |
| Format | Text-based | Binary |
| Data types | String, Number, Boolean, Array, Object, null | All JSON types + Date, ObjectId, Binary, Decimal128, etc. |
| Speed | Slower to parse | Faster for MongoDB to encode/decode |
| Size | Smaller text | Slightly larger binary |
| Readable | ✅ Human-readable | ❌ Not directly readable |

```javascript
// JSON has no Date type — dates are strings
{ "createdAt": "2024-01-15T10:00:00Z" } // JSON string

// BSON has native Date type
{ "createdAt": ISODate("2024-01-15T10:00:00Z") } // BSON Date object

// ObjectId — BSON's unique identifier (12-byte)
{ "_id": ObjectId("64a1b2c3d4e5f6g7h8i9j0k1") }
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 18. What are collections and documents in MongoDB?

| Concept | Relational Equivalent | Description |
| ------- | --------------------- | ----------- |
| **Database** | Database | Container for collections |
| **Collection** | Table | Group of related documents |
| **Document** | Row | Individual data record (BSON object) |
| **Field** | Column | Key-value pair within a document |
| **`_id`** | Primary Key | Unique identifier — auto-generated as ObjectId |

```javascript
// Database: "shopdb"
// Collection: "products"
// Documents:

{ _id: ObjectId("..."), name: "Laptop", price: 50000, stock: 10 }
{ _id: ObjectId("..."), name: "Phone",  price: 25000, stock: 50, color: "black" }
// ↑ Different fields are allowed in the same collection (flexible schema)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 19. What is Mongoose? Why is it used with MongoDB?

Mongoose is an **ODM (Object Document Mapper)** library for MongoDB and Node.js. It provides a schema-based solution to model your application data.

**Why Mongoose over raw MongoDB driver:**

| Feature | Raw MongoDB Driver | Mongoose |
| ------- | ------------------ | -------- |
| Schema validation | ❌ Manual | ✅ Built-in |
| Model creation | ❌ Manual | ✅ `mongoose.model()` |
| Middleware (hooks) | ❌ No | ✅ pre/post hooks |
| Population (joins) | ❌ Manual aggregation | ✅ `.populate()` |
| Virtuals | ❌ No | ✅ Yes |
| TypeScript support | Basic | ✅ Excellent |

```javascript
const mongoose = require('mongoose');

// Connect to MongoDB
mongoose.connect(process.env.MONGODB_URI)
  .then(() => console.log('MongoDB connected'))
  .catch(err => console.error('Connection error:', err));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 20. What are Mongoose Schemas and Models?

A **Schema** defines the structure, data types, and validation rules for documents. A **Model** is a compiled version of the schema that provides the interface to interact with the collection.

```javascript
const mongoose = require('mongoose');

// 1. Define Schema
const userSchema = new mongoose.Schema({
  name: {
    type: String,
    required: [true, 'Name is required'],
    trim: true,
    minlength: 2,
    maxlength: 50
  },
  email: {
    type: String,
    required: true,
    unique: true,
    lowercase: true,
    match: [/\S+@\S+\.\S+/, 'Please enter a valid email']
  },
  password: { type: String, required: true, select: false }, // excluded from queries by default
  role: { type: String, enum: ['user', 'admin', 'editor'], default: 'user' },
  age: { type: Number, min: 0, max: 120 },
  isActive: { type: Boolean, default: true },
  skills: [String], // array of strings
  address: {        // nested object
    city: String,
    state: String
  }
}, {
  timestamps: true // auto-adds createdAt and updatedAt
});

// 2. Compile to Model (maps to "users" collection)
const User = mongoose.model('User', userSchema);

module.exports = User;
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 21. What are the basic CRUD operations in MongoDB?

```javascript
const User = require('./models/User');

// CREATE
const newUser = await User.create({
  name: 'Sisi',
  email: 'sisi@webortex.com',
  password: hashedPassword,
  role: 'admin'
});

// READ
const allUsers  = await User.find();                             // all documents
const oneUser   = await User.findById(id);                      // by _id
const filtered  = await User.find({ role: 'admin', isActive: true }); // with filter
const oneByEmail = await User.findOne({ email: 'sisi@webortex.com' });

// Chaining query operators
const users = await User
  .find({ role: 'user' })
  .select('name email -password')  // include name, email; exclude password
  .sort({ createdAt: -1 })         // newest first
  .limit(10)
  .skip(20);                       // for pagination

// UPDATE
const updated = await User.findByIdAndUpdate(
  id,
  { $set: { name: 'Sisindri', role: 'editor' } },
  { new: true, runValidators: true } // return updated doc, run schema validators
);

// DELETE
await User.findByIdAndDelete(id);
await User.deleteMany({ isActive: false }); // bulk delete
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 22. What are indexes in MongoDB? Why are they important?

Indexes are **special data structures** that store a small portion of the collection's data in an easy-to-traverse form — making queries much faster by avoiding full collection scans.

```javascript
// Without index: MongoDB scans EVERY document (O(n))
// With index: MongoDB uses B-tree to find documents (O(log n))

// In Mongoose Schema — define indexes:
const productSchema = new mongoose.Schema({
  name: { type: String, index: true },          // single field index
  email: { type: String, unique: true },         // unique index
  price: Number,
  category: String,
  createdAt: Date
});

// Compound index (for queries that filter by both fields)
productSchema.index({ category: 1, price: -1 }); // 1 = asc, -1 = desc

// Text index for full-text search
productSchema.index({ name: 'text', description: 'text' });

// In MongoDB shell / scripts:
// db.products.createIndex({ name: 1 })
// db.products.getIndexes()
// db.products.dropIndex({ name: 1 })

// Check if a query uses an index (explain plan):
// db.products.find({ category: 'electronics' }).explain('executionStats')
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — Node.js

<br>

### 23. What is Node.js? Why is it used in MERN?

Node.js is a **server-side JavaScript runtime environment** built on Chrome's V8 JavaScript engine. It allows JavaScript to run outside the browser — on the server.

**Why Node.js in MERN:**

| Reason | Description |
| ------ | ----------- |
| **JavaScript on server** | Same language as React frontend — shared code possible |
| **Non-blocking I/O** | Handles thousands of concurrent connections efficiently |
| **npm ecosystem** | Largest package registry in the world |
| **Event-driven** | Perfect for real-time apps (chat, notifications) |
| **Fast** | V8 engine + non-blocking = high performance |
| **JSON native** | MongoDB returns JSON → Node.js handles it natively |

```javascript
// Node.js can run JS outside the browser
// node server.js — starts your backend
const http = require('http');

const server = http.createServer((req, res) => {
  res.writeHead(200, { 'Content-Type': 'application/json' });
  res.end(JSON.stringify({ message: 'Hello from Node.js!' }));
});

server.listen(5000, () => console.log('Server running on port 5000'));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 24. What is the difference between Node.js and a browser JavaScript engine?

| Feature | Browser JS | Node.js |
| ------- | ---------- | ------- |
| Environment | Client-side | Server-side |
| DOM access | ✅ Yes | ❌ No |
| `window` / `document` | ✅ Yes | ❌ No |
| File system access | ❌ No | ✅ Yes (`fs` module) |
| HTTP server | ❌ No | ✅ Yes (`http` module) |
| Global object | `window` | `global` / `globalThis` |
| Module system | ESM (`import/export`) | CommonJS (`require`) or ESM |
| Built-in modules | Web APIs | `fs`, `path`, `os`, `crypto`, `http`, etc. |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 25. What are Node.js modules? What is require vs import?

Node.js modules are **reusable pieces of code** in separate files. There are two module systems:

```javascript
// CommonJS (traditional Node.js) — uses require/module.exports
// math.js
const add = (a, b) => a + b;
const multiply = (a, b) => a * b;
module.exports = { add, multiply };

// server.js
const { add, multiply } = require('./math');
const express = require('express'); // npm package

// ES Modules (modern — "type": "module" in package.json)
// math.js
export const add = (a, b) => a + b;
export default multiply;

// server.js
import { add } from './math.js';
import multiply from './math.js';
import express from 'express';

// Built-in modules
const fs = require('fs');      // file system
const path = require('path');  // file paths
const os = require('os');      // operating system info
const crypto = require('crypto'); // cryptography
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — Express.js

<br>

### 26. What is Express.js? Why is it used in MERN?

Express.js is a **minimal, flexible Node.js web application framework** that provides a robust set of features for building REST APIs and web apps.

**Why Express in MERN:**
- Handles HTTP routing simply and cleanly
- Middleware pipeline for auth, logging, parsing, error handling
- Integrates seamlessly with Mongoose/MongoDB
- Large ecosystem of middleware packages

```javascript
// Without Express — raw Node.js HTTP (verbose)
const http = require('http');
const server = http.createServer((req, res) => {
  if (req.url === '/api/users' && req.method === 'GET') {
    res.writeHead(200, { 'Content-Type': 'application/json' });
    res.end(JSON.stringify(users));
  }
  // handle every route manually...
});

// With Express — clean and simple
const express = require('express');
const app = express();
app.get('/api/users', (req, res) => res.json(users));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 27. How do you create a basic Express server?

```javascript
const express = require('express');
const mongoose = require('mongoose');
const cors = require('cors');
require('dotenv').config();

const app = express();

// ── Middleware ──────────────────────────────
app.use(cors({ origin: process.env.CLIENT_URL }));
app.use(express.json());            // parse JSON bodies
app.use(express.urlencoded({ extended: true })); // parse form data

// ── Routes ──────────────────────────────────
app.use('/api/users', require('./routes/userRoutes'));
app.use('/api/posts', require('./routes/postRoutes'));

// ── Health check ────────────────────────────
app.get('/health', (req, res) => res.json({ status: 'OK' }));

// ── 404 handler ─────────────────────────────
app.use((req, res) => res.status(404).json({ message: 'Route not found' }));

// ── Global error handler ────────────────────
app.use((err, req, res, next) => {
  console.error(err.stack);
  res.status(err.status || 500).json({ message: err.message || 'Server Error' });
});

// ── Connect DB + Start Server ────────────────
const PORT = process.env.PORT || 5000;

mongoose.connect(process.env.MONGODB_URI)
  .then(() => app.listen(PORT, () => console.log(`Server running on port ${PORT}`)))
  .catch(err => console.error('DB Connection failed:', err));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 28. What is middleware in Express.js?

Middleware are **functions that have access to `req`, `res`, and `next`** — they execute during the request-response cycle. Each middleware can modify the request, send a response, or pass control to the next middleware via `next()`.

```javascript
// Middleware signature
function middlewareName(req, res, next) {
  // do something with req or res
  next(); // pass to next middleware (or route handler)
  // if you don't call next(), the request hangs!
}

// Example 1: Logging middleware
app.use((req, res, next) => {
  console.log(`[${new Date().toISOString()}] ${req.method} ${req.url}`);
  next();
});

// Example 2: Auth middleware
const protect = async (req, res, next) => {
  try {
    const token = req.headers.authorization?.split(' ')[1];
    if (!token) return res.status(401).json({ message: 'No token' });
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = await User.findById(decoded.id).select('-password');
    next();
  } catch (err) {
    res.status(401).json({ message: 'Token invalid' });
  }
};

// Apply to specific routes
app.get('/api/profile', protect, (req, res) => {
  res.json(req.user); // user set by middleware
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 29. What are the HTTP methods and how are they used in Express routing?

| HTTP Method | Express Method | REST Usage | Idempotent? |
| ----------- | -------------- | ---------- | ----------- |
| GET | `app.get()` | Retrieve data | ✅ Yes |
| POST | `app.post()` | Create resource | ❌ No |
| PUT | `app.put()` | Replace entire resource | ✅ Yes |
| PATCH | `app.patch()` | Partially update resource | ✅ Yes |
| DELETE | `app.delete()` | Delete resource | ✅ Yes |

```javascript
const express = require('express');
const router = express.Router();

router.get('/', getAllUsers);          // GET   /api/users
router.post('/', createUser);          // POST  /api/users
router.get('/:id', getUserById);       // GET   /api/users/:id
router.put('/:id', replaceUser);       // PUT   /api/users/:id
router.patch('/:id', updateUser);      // PATCH /api/users/:id
router.delete('/:id', deleteUser);     // DELETE /api/users/:id

module.exports = router;
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 30. What is the difference between req.params, req.query, and req.body?

| Property | Source | Example URL / Request | Use case |
| -------- | ------ | --------------------- | -------- |
| `req.params` | URL path segments | `/users/:id` → `/users/42` | Resource identifiers |
| `req.query` | URL query string | `/users?page=2&limit=10` | Filtering, pagination |
| `req.body` | Request body (POST/PUT/PATCH) | JSON body `{ "name": "Sisi" }` | Creating / updating data |

```javascript
// Route: GET /api/products/:category?page=1&limit=10
app.get('/api/products/:category', (req, res) => {
  const { category } = req.params;   // "electronics"
  const { page, limit } = req.query; // "1", "10" (strings!)
  console.log(category, page, limit);
});

// Route: POST /api/users  (body: {"name": "Sisi", "email": "s@s.com"})
app.post('/api/users', (req, res) => {
  const { name, email } = req.body;  // requires express.json() middleware
  console.log(name, email);
});

// req.headers — access request headers
const token = req.headers.authorization; // "Bearer eyJ..."
const contentType = req.headers['content-type'];
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — MongoDB Deep Dive

<br>

### 31. What is the MongoDB Aggregation Pipeline?

The Aggregation Pipeline is a **multi-stage data processing framework** where documents pass through a series of stages — each stage transforms the data in some way.

```javascript
// Example: Get total sales per category, sorted by revenue
const result = await Order.aggregate([
  // Stage 1: Filter — only completed orders
  { $match: { status: 'completed', createdAt: { $gte: new Date('2024-01-01') } } },

  // Stage 2: Join with products collection
  { $lookup: {
    from: 'products',
    localField: 'productId',
    foreignField: '_id',
    as: 'product'
  }},

  // Stage 3: Unwind array from $lookup
  { $unwind: '$product' },

  // Stage 4: Group by category, calculate totals
  { $group: {
    _id: '$product.category',
    totalRevenue: { $sum: { $multiply: ['$quantity', '$product.price'] } },
    orderCount: { $sum: 1 },
    avgOrderValue: { $avg: '$totalAmount' }
  }},

  // Stage 5: Sort by revenue descending
  { $sort: { totalRevenue: -1 } },

  // Stage 6: Limit results
  { $limit: 10 },

  // Stage 7: Reshape output
  { $project: { category: '$_id', totalRevenue: 1, orderCount: 1, _id: 0 } }
]);
```

**Common aggregation stages:** `$match`, `$group`, `$sort`, `$limit`, `$skip`, `$project`, `$lookup`, `$unwind`, `$addFields`, `$count`, `$facet`

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 32. How does MongoDB handle relationships? What are embedding vs referencing strategies?

MongoDB doesn't enforce relationships natively. You choose between **embedding** (denormalization) or **referencing** (normalization).

```javascript
// ── STRATEGY 1: EMBEDDING ──
// Store related data inside the same document
// ✅ Best for: data always read together, one-to-few relationships, fast reads
{
  _id: ObjectId("..."),
  name: "Sisi",
  // Address embedded — no separate collection needed
  address: { city: "Tirupati", state: "AP", pincode: "517501" },
  // Social links embedded
  social: { instagram: "@sisi_tarakk", linkedin: "sisitarak" }
}

// ── STRATEGY 2: REFERENCING ──
// Store ObjectId references to documents in other collections
// ✅ Best for: many-to-many, large sub-documents, data updated independently

// User document
{ _id: ObjectId("userId1"), name: "Sisi", role: "admin" }

// Post document — references user by ID
{ _id: ObjectId("postId1"), title: "My Blog", author: ObjectId("userId1") }

// Fetch with populate (Mongoose)
const post = await Post.findById(id).populate('author', 'name email avatar');
// post.author → { name: "Sisi", email: "...", avatar: "..." }
```

| Criteria | Embedding | Referencing |
| -------- | --------- | ----------- |
| Read performance | ✅ Faster (one query) | ❌ Slower (multiple queries or $lookup) |
| Write performance | ❌ Updates affect whole document | ✅ Independent updates |
| Document size | Can hit 16MB BSON limit | ✅ No limit |
| Data duplication | ❌ Possible | ✅ Normalized |
| Use for | One-to-few, static data | One-to-many, many-to-many |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 33. What is population in Mongoose?

Mongoose `populate()` **replaces referenced ObjectIds** with the actual documents from other collections — similar to a SQL JOIN.

```javascript
const postSchema = new mongoose.Schema({
  title: String,
  content: String,
  author: { type: mongoose.Schema.Types.ObjectId, ref: 'User' },  // reference
  tags: [{ type: mongoose.Schema.Types.ObjectId, ref: 'Tag' }]    // array of refs
});

// Basic populate
const post = await Post
  .findById(postId)
  .populate('author')                          // full user document
  .populate('tags', 'name color -_id');        // only name and color fields

// Nested populate — populate author, then author's company
const post = await Post.findById(postId)
  .populate({
    path: 'author',
    select: 'name email avatar',
    populate: { path: 'company', select: 'name logo' }
  });

// post.author → { name: "Sisi", email: "...", company: { name: "Webortex" } }
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 34. What are MongoDB transactions?

MongoDB transactions (introduced in 4.0) allow **multiple operations across multiple documents/collections to be executed atomically** — all succeed or all fail (ACID-compliant).

```javascript
// Use transactions for operations that must succeed together
// Example: Transfer money between two accounts

const session = await mongoose.startSession();

try {
  session.startTransaction();

  await Account.findByIdAndUpdate(
    senderId,
    { $inc: { balance: -amount } },
    { session, new: true }
  );

  await Account.findByIdAndUpdate(
    receiverId,
    { $inc: { balance: +amount } },
    { session, new: true }
  );

  await Transaction.create([{
    from: senderId, to: receiverId, amount
  }], { session });

  await session.commitTransaction();  // all operations succeed
  console.log('Transfer successful');

} catch (error) {
  await session.abortTransaction();   // all operations rolled back
  throw error;
} finally {
  session.endSession();
}
```

> **Note:** Transactions require a **Replica Set** (even in development — use `mongod --replSet rs0` or MongoDB Atlas).

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 35. What is sharding in MongoDB?

Sharding is MongoDB's method for **distributing data across multiple servers (shards)** to handle large data volumes and high throughput beyond a single machine's capability.

```
Horizontal Scaling via Sharding:

Client App
     ↓
mongos (query router)
     ↓
Config Servers (metadata — where is each data chunk?)
     ↓ ↓ ↓
Shard 1  Shard 2  Shard 3
(data A-M) (data N-Z) (overflow)
```

**Shard key** — the field used to distribute data across shards:
```javascript
// Example: Shard "orders" collection by userId
// db.adminCommand({ shardCollection: "shop.orders", key: { userId: 1 } })

// Good shard keys: high cardinality, even distribution, commonly queried
// Bad shard keys: monotonically increasing (_id), low cardinality (boolean)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 36. What is replication in MongoDB?

Replication is the process of **synchronizing data across multiple MongoDB instances** (a Replica Set) to provide redundancy and high availability.

```
Primary Node (accepts reads + writes)
     ↓ oplog sync
Secondary Node 1 (read replica, failover candidate)
     ↓ oplog sync
Secondary Node 2 (read replica, failover candidate)

If Primary goes down → Secondaries elect a new Primary (automatic failover)
```

**Benefits:**
- **High availability** — automatic failover if primary fails
- **Data redundancy** — no single point of failure
- **Read scaling** — route read queries to secondaries
- **Required for transactions** — MongoDB transactions need a replica set

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 37. How do you validate data in Mongoose?

```javascript
const userSchema = new mongoose.Schema({
  // Built-in validators
  name: {
    type: String,
    required: [true, 'Name is required'],
    minlength: [2, 'Name must be at least 2 characters'],
    maxlength: [50, 'Name cannot exceed 50 characters'],
    trim: true
  },
  email: {
    type: String,
    required: true,
    unique: true,
    match: [/^\S+@\S+\.\S+$/, 'Please enter a valid email']
  },
  age: { type: Number, min: [0, 'Age cannot be negative'], max: 120 },
  role: { type: String, enum: { values: ['user', 'admin'], message: 'Invalid role' } },

  // Custom validator
  phone: {
    type: String,
    validate: {
      validator: function(v) {
        return /^\d{10}$/.test(v); // 10-digit number
      },
      message: props => `${props.value} is not a valid phone number`
    }
  }
});

// Mongoose pre-save hook for additional validation
userSchema.pre('save', async function(next) {
  if (this.isModified('password')) {
    this.password = await bcrypt.hash(this.password, 12);
  }
  next();
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Node.js Deep Dive

<br>

### 38. What is the Node.js Event Loop in depth?

The Node.js Event Loop is what enables **non-blocking I/O** despite JavaScript being single-threaded. It continuously checks the call stack and processes callbacks from different queues.

```
Event Loop Phases (in order):
┌──────────────────────────────────────────────────────┐
│ 1. timers         → setTimeout, setInterval callbacks │
│ 2. pending I/O    → I/O callbacks deferred to loop   │
│ 3. idle/prepare   → internal use only                │
│ 4. poll           → retrieve new I/O events (blocks) │
│ 5. check          → setImmediate callbacks           │
│ 6. close events   → socket.on('close', ...) etc.     │
└──────────────────────────────────────────────────────┘
Between each phase: process microtasks (Promises + process.nextTick)
```

```javascript
console.log('1'); // sync

setImmediate(() => console.log('5 - setImmediate'));   // check phase
setTimeout(() => console.log('4 - setTimeout'), 0);    // timers phase
Promise.resolve().then(() => console.log('3 - Promise')); // microtask
process.nextTick(() => console.log('2 - nextTick'));    // highest priority microtask

console.log('1b'); // sync

// Output: 1, 1b, 2, 3, 4, 5
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 39. What is non-blocking I/O in Node.js?

Non-blocking I/O means Node.js **initiates I/O operations (disk reads, network requests, DB queries) and immediately moves on** — it doesn't wait for them to complete. When the operation finishes, a callback/promise is triggered.

```javascript
// ❌ Blocking — server is frozen during file read
const data = fs.readFileSync('bigfile.txt'); // blocks event loop
// No other requests can be handled while this runs!

// ✅ Non-blocking — server continues handling other requests
fs.readFile('bigfile.txt', (err, data) => {
  if (err) throw err;
  console.log(data); // runs when file is ready
});
// Server immediately continues and can handle other requests

// With async/await (non-blocking under the hood)
async function readConfig() {
  const data = await fs.promises.readFile('config.json', 'utf8');
  return JSON.parse(data);
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 40. What is the difference between process.nextTick(), setImmediate(), and setTimeout()?

| Method | Queue | Runs | Priority |
| ------ | ----- | ---- | -------- |
| `process.nextTick(cb)` | nextTick queue | Before next event loop phase | 🔴 Highest |
| `Promise.then(cb)` | Microtask queue | Before next event loop phase | 🔴 High |
| `setImmediate(cb)` | Check phase | After current poll phase | 🟡 Medium |
| `setTimeout(cb, 0)` | Timers phase | Next timers phase | 🟢 Lower |

```javascript
setImmediate(() => console.log('4 - setImmediate'));
setTimeout(() => console.log('5 - setTimeout'), 0);
Promise.resolve().then(() => console.log('3 - Promise'));
process.nextTick(() => console.log('2 - nextTick'));
console.log('1 - sync');

// Output: 1, 2, 3, 4, 5 (setImmediate usually before setTimeout)
```

> **Use case:** `process.nextTick()` is useful to ensure a callback runs after current code but before any I/O. Overusing it can starve the event loop.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 41. What are Node.js streams?

Streams are objects that allow **reading or writing data piece by piece** (chunk by chunk), without loading the entire data into memory — essential for handling large files or continuous data.

```javascript
const fs = require('fs');
const zlib = require('zlib');

// ❌ Without streams — loads entire file into memory
const data = fs.readFileSync('largefile.csv'); // could be 2GB!
res.send(data);

// ✅ With streams — processes chunk by chunk
fs.createReadStream('largefile.csv')
  .pipe(zlib.createGzip())   // compress on-the-fly
  .pipe(res);                // send to HTTP response

// Types of streams:
// Readable  — fs.createReadStream(), req (HTTP request)
// Writable  — fs.createWriteStream(), res (HTTP response)
// Duplex    — net.Socket (both read and write)
// Transform — zlib.createGzip() (read, transform, write)

// Stream events
const readable = fs.createReadStream('file.txt');
readable.on('data', chunk => console.log('Chunk:', chunk.length, 'bytes'));
readable.on('end', () => console.log('Done reading'));
readable.on('error', err => console.error('Error:', err));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 42. What is clustering in Node.js?

Node.js runs on a single thread. **Clustering spawns multiple worker processes** (one per CPU core) that all share the same server port — enabling full use of multi-core systems.

```javascript
const cluster = require('cluster');
const os = require('os');
const app = require('./app');

const NUM_CPUS = os.cpus().length;

if (cluster.isMaster) {
  console.log(`Master ${process.pid} is running`);

  // Fork worker for each CPU core
  for (let i = 0; i < NUM_CPUS; i++) {
    cluster.fork();
  }

  // Restart crashed workers
  cluster.on('exit', (worker, code) => {
    console.log(`Worker ${worker.process.pid} died. Restarting...`);
    cluster.fork();
  });

} else {
  // Each worker runs the Express app
  app.listen(5000, () => {
    console.log(`Worker ${process.pid} started`);
  });
}
// Result: 8 workers on an 8-core machine, all listening on port 5000
```

> **Modern alternative:** Use **PM2** process manager which handles clustering automatically: `pm2 start server.js -i max`

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 43. What is the difference between spawn, exec, and fork in Node.js?

All three are from the `child_process` module for running external processes:

| Method | Returns | Use case | Output buffered? |
| ------ | ------- | -------- | --------------- |
| `spawn` | Stream | Large output, real-time data (video encoding, long-running) | ❌ No (streaming) |
| `exec` | Buffer | Short commands, shell scripts | ✅ Yes (in memory) |
| `fork` | ChildProcess | Run another Node.js script with IPC | ✅ With IPC messages |

```javascript
const { spawn, exec, fork } = require('child_process');

// exec — run shell command, get buffered output
exec('ls -la', (error, stdout, stderr) => {
  console.log(stdout);
});

// spawn — stream large output
const ls = spawn('ls', ['-la', '/usr']);
ls.stdout.on('data', data => process.stdout.write(data));

// fork — run Node.js script with messaging
const worker = fork('./worker.js');
worker.send({ task: 'heavyComputation', data: largeArray });
worker.on('message', result => console.log('Result:', result));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 44. What are environment variables and how do you use them in Node.js?

Environment variables are **key-value pairs stored outside the code** used to configure the app differently for development, staging, and production — without changing code.

```bash
# .env file (NEVER commit to git)
NODE_ENV=development
PORT=5000
MONGODB_URI=mongodb+srv://user:pass@cluster.mongodb.net/mydb
JWT_SECRET=superSecretKey123!@#
JWT_EXPIRES_IN=7d
CLIENT_URL=http://localhost:3000
EMAIL_SERVICE=SendGrid
EMAIL_API_KEY=SG.xxxxxxxxxx
```

```javascript
// Install: npm install dotenv
require('dotenv').config(); // load .env into process.env (call at the top of server.js)

const PORT = process.env.PORT || 5000;
const MONGODB_URI = process.env.MONGODB_URI;
const JWT_SECRET = process.env.JWT_SECRET;

// Never hardcode secrets in code:
// ❌ const secret = 'superSecretKey123';
// ✅ const secret = process.env.JWT_SECRET;

// Access in any module after dotenv is loaded
mongoose.connect(process.env.MONGODB_URI);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Express.js Deep Dive

<br>

### 45. What are the types of middleware in Express.js?

```javascript
// 1. Application-level middleware — applies to all routes
app.use(express.json());
app.use(cors());

// 2. Router-level middleware — applies to routes in a specific router
const router = express.Router();
router.use(protect); // all routes in this router require auth

// 3. Error-handling middleware — 4 parameters (must be last)
app.use((err, req, res, next) => {
  res.status(err.status || 500).json({ message: err.message });
});

// 4. Built-in middleware
app.use(express.json());                        // parse JSON bodies
app.use(express.urlencoded({ extended: true })); // parse URL-encoded bodies
app.use(express.static('public'));               // serve static files

// 5. Third-party middleware
const morgan = require('morgan');    // HTTP request logger
const helmet = require('helmet');    // security headers
const rateLimit = require('express-rate-limit');

app.use(morgan('dev'));
app.use(helmet());
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 46. How do you handle errors in Express.js?

```javascript
// ── Async error wrapper — avoids try/catch in every route ──
const asyncHandler = (fn) => (req, res, next) => {
  Promise.resolve(fn(req, res, next)).catch(next);
};

// ── Custom Error class ──
class AppError extends Error {
  constructor(message, statusCode) {
    super(message);
    this.statusCode = statusCode;
    this.isOperational = true; // expected errors (vs programming bugs)
  }
}

// ── Route with error handling ──
app.get('/api/users/:id', asyncHandler(async (req, res, next) => {
  const user = await User.findById(req.params.id);
  if (!user) {
    return next(new AppError('User not found', 404)); // pass to error middleware
  }
  res.json(user);
}));

// ── Global error handler (must be LAST middleware, 4 parameters) ──
app.use((err, req, res, next) => {
  let { statusCode = 500, message } = err;

  // Handle specific MongoDB errors
  if (err.name === 'CastError') { statusCode = 400; message = 'Invalid ID format'; }
  if (err.code === 11000) { statusCode = 409; message = 'Duplicate field value'; }
  if (err.name === 'ValidationError') {
    statusCode = 400;
    message = Object.values(err.errors).map(e => e.message).join(', ');
  }

  if (process.env.NODE_ENV === 'development') {
    res.status(statusCode).json({ message, stack: err.stack });
  } else {
    res.status(statusCode).json({ message: err.isOperational ? message : 'Server Error' });
  }
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 47. What is Express Router and why is it used?

`express.Router()` creates a **modular, mountable route handler** — allowing you to split routes into separate files rather than defining everything in `server.js`.

```javascript
// routes/userRoutes.js
const express = require('express');
const router = express.Router();
const { protect, restrictTo } = require('../middleware/auth');
const { getAllUsers, getUser, updateUser, deleteUser } = require('../controllers/userController');

router.use(protect); // all routes below require authentication

router.route('/')
  .get(getAllUsers)
  .post(createUser);

router.route('/:id')
  .get(getUser)
  .patch(updateUser)
  .delete(restrictTo('admin'), deleteUser); // only admins can delete

module.exports = router;

// server.js — mount the router
app.use('/api/v1/users', require('./routes/userRoutes'));
app.use('/api/v1/posts', require('./routes/postRoutes'));
app.use('/api/v1/auth',  require('./routes/authRoutes'));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 48. How do you serve static files in Express.js?

```javascript
const path = require('path');

// Serve static files from "public" directory
app.use(express.static(path.join(__dirname, 'public')));
// Now: GET /images/logo.png → serves public/images/logo.png

// Serve uploaded files
app.use('/uploads', express.static(path.join(__dirname, 'uploads')));
// GET /uploads/profile.jpg → serves uploads/profile.jpg

// Serve React build (for full-stack deployment)
app.use(express.static(path.join(__dirname, 'client/build')));

// Catch-all: serve React app for any non-API route (SPA routing)
app.get('*', (req, res) => {
  res.sendFile(path.join(__dirname, 'client/build', 'index.html'));
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 49. What is the difference between app.use() and app.get()?

| Feature | `app.use()` | `app.get()` |
| ------- | ----------- | ----------- |
| HTTP methods | All methods | GET only |
| Path matching | Prefix match (`/api` matches `/api/users`) | Exact match |
| Use case | Middleware, mounting routers | Defining GET route handlers |

```javascript
// app.use — matches ANY method, path prefix
app.use('/api', router);          // mounts router for all /api/* routes
app.use(express.json());          // applies to ALL routes
app.use('/uploads', express.static('uploads')); // serve static

// app.get — only GET, exact path
app.get('/api/users', getAllUsers);  // only GET /api/users
app.get('/api/users/:id', getUser);  // only GET /api/users/:id

// Equivalent for other methods:
app.post(), app.put(), app.patch(), app.delete()
// Or handle all methods:
app.all('/api/secret', (req, res) => res.status(403).json({ message: 'Forbidden' }));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 50. How do you implement rate limiting in Express.js?

Rate limiting **restricts the number of requests** a client can make in a given time window — protecting against brute force attacks and abuse.

```javascript
const rateLimit = require('express-rate-limit');

// General rate limiter
const limiter = rateLimit({
  windowMs: 15 * 60 * 1000, // 15 minutes
  max: 100,                  // max 100 requests per windowMs
  message: { error: 'Too many requests, please try again after 15 minutes.' },
  standardHeaders: true,     // include RateLimit headers in response
  legacyHeaders: false
});

// Strict limiter for auth endpoints (prevent brute force)
const authLimiter = rateLimit({
  windowMs: 60 * 60 * 1000, // 1 hour
  max: 10,                   // only 10 login attempts per hour per IP
  message: { error: 'Too many login attempts. Account locked for 1 hour.' }
});

// Apply globally
app.use('/api', limiter);

// Apply to specific sensitive routes
app.use('/api/auth/login', authLimiter);
app.use('/api/auth/forgot-password', authLimiter);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Authentication & Security

<br>

### 51. What is JWT (JSON Web Token)? How does it work?

JWT is a **compact, URL-safe token** used to securely transmit information between parties. It's the most common authentication mechanism in MERN apps.

**JWT structure:** `header.payload.signature`

```
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9   ← Header (Base64: algorithm + type)
.eyJ1c2VySWQiOiI2NGExYjJjMyIsInJvbGUiOiJ1c2VyIiwiaWF0IjoxNjE2MjM5MDIyfQ  ← Payload
.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c ← Signature (HMAC-SHA256)
```

```javascript
const jwt = require('jsonwebtoken');

// Generate token (on login)
const generateToken = (userId, role) => {
  return jwt.sign(
    { userId, role },              // payload
    process.env.JWT_SECRET,        // secret key
    { expiresIn: process.env.JWT_EXPIRES_IN } // '7d', '1h', etc.
  );
};

// Verify token (in auth middleware)
const decoded = jwt.verify(token, process.env.JWT_SECRET);
// decoded → { userId: '64a1b2c3', role: 'user', iat: ..., exp: ... }

// Token flow:
// 1. User logs in → server generates JWT → sends to client
// 2. Client stores token (localStorage or HTTP-only cookie)
// 3. Client sends token in Authorization header: "Bearer <token>"
// 4. Server verifies token on every protected request
// 5. Token expires → user must log in again (or use refresh token)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 52. How do you implement authentication in a MERN app?

```javascript
// ── authController.js ──

const register = asyncHandler(async (req, res) => {
  const { name, email, password } = req.body;
  if (await User.findOne({ email })) {
    return res.status(409).json({ message: 'Email already in use' });
  }
  const user = await User.create({ name, email, password }); // password hashed in pre-save hook
  const token = generateToken(user._id, user.role);
  res.status(201).json({ token, user: { id: user._id, name, email, role: user.role } });
});

const login = asyncHandler(async (req, res) => {
  const { email, password } = req.body;
  const user = await User.findOne({ email }).select('+password');
  if (!user || !(await bcrypt.compare(password, user.password))) {
    return res.status(401).json({ message: 'Invalid email or password' });
  }
  const token = generateToken(user._id, user.role);
  res.json({ token, user: { id: user._id, name: user.name, email, role: user.role } });
});

// ── React side ── (store token, attach to requests)
// Login
const { token } = await axios.post('/api/auth/login', credentials);
localStorage.setItem('token', token); // or use HTTP-only cookie

// Axios interceptor — auto-attach token
axios.interceptors.request.use(config => {
  const token = localStorage.getItem('token');
  if (token) config.headers.Authorization = `Bearer ${token}`;
  return config;
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 53. What is the difference between authentication and authorization?

| Concept | Authentication | Authorization |
| ------- | -------------- | ------------- |
| Question | "Who are you?" | "What can you do?" |
| Verifies | Identity | Permissions |
| How | Login (password, biometric, OAuth) | JWT claims, roles, RBAC |
| Example | User logs in with email + password | Admin can delete; user can only read |
| HTTP Status | 401 Unauthorized | 403 Forbidden |

```javascript
// Authentication middleware — verifies WHO you are
const protect = async (req, res, next) => {
  const token = req.headers.authorization?.split(' ')[1];
  if (!token) return res.status(401).json({ message: 'Not authenticated' });
  const decoded = jwt.verify(token, process.env.JWT_SECRET);
  req.user = await User.findById(decoded.userId);
  next();
};

// Authorization middleware — verifies WHAT you can do
const restrictTo = (...roles) => (req, res, next) => {
  if (!roles.includes(req.user.role)) {
    return res.status(403).json({ message: 'You do not have permission' });
  }
  next();
};

// Usage
router.delete('/:id', protect, restrictTo('admin'), deleteUser);
// protect → checks JWT (authentication)
// restrictTo → checks role (authorization)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 54. What is bcrypt and why is it used?

bcrypt is a **password hashing library** that uses an adaptive hashing algorithm with a configurable cost factor — making it computationally expensive to brute-force.

```javascript
const bcrypt = require('bcryptjs');

// Hashing password before saving
userSchema.pre('save', async function(next) {
  if (!this.isModified('password')) return next(); // only hash if password changed
  this.password = await bcrypt.hash(this.password, 12); // 12 = cost factor (higher = slower = safer)
  next();
});

// Comparing password on login
const isCorrect = await bcrypt.compare(candidatePassword, this.password);
// candidatePassword = plain text from login form
// this.password = hashed value stored in DB
// Returns: true or false

// Why bcrypt over MD5/SHA256?
// MD5/SHA256 are fast → easy to brute force
// bcrypt is slow by design → computationally expensive per attempt
// bcrypt includes a random salt → same password → different hash each time
// MD5: "password" → always "5f4dcc3b5aa765d61d8327deb882cf99"
// bcrypt: "password" → "$2b$12$uniqueSalt....." (different every time)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 55. What is an HTTP-only cookie? Why is it more secure than localStorage for JWT?

| Storage | XSS Vulnerable | CSRF Vulnerable | Accessible via JS |
| ------- | -------------- | --------------- | ----------------- |
| `localStorage` | ✅ Yes — JS can read it | ❌ No | ✅ Yes |
| HTTP-only Cookie | ❌ No — JS cannot read it | ✅ Yes (need CSRF token) | ❌ No |

```javascript
// Server — set JWT in HTTP-only cookie
res.cookie('token', jwtToken, {
  httpOnly: true,    // JS cannot access — prevents XSS theft
  secure: true,      // only over HTTPS in production
  sameSite: 'strict', // prevents CSRF
  maxAge: 7 * 24 * 60 * 60 * 1000 // 7 days in ms
});

// Server — read from cookie
const cookieParser = require('cookie-parser');
app.use(cookieParser());
const token = req.cookies.token; // automatically sent with every request

// Server — clear cookie on logout
res.clearCookie('token');

// React — no need to manually attach token; browser sends cookie automatically
// axios.defaults.withCredentials = true; // required for cross-origin cookies
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 56. What is OAuth 2.0? How is it used in MERN apps?

OAuth 2.0 is an **authorization framework** that allows users to log in using existing accounts (Google, GitHub, Facebook) — without sharing their passwords.

```javascript
// Using Passport.js with Google OAuth in Express
const passport = require('passport');
const GoogleStrategy = require('passport-google-oauth20').Strategy;

passport.use(new GoogleStrategy({
  clientID: process.env.GOOGLE_CLIENT_ID,
  clientSecret: process.env.GOOGLE_CLIENT_SECRET,
  callbackURL: '/api/auth/google/callback'
}, async (accessToken, refreshToken, profile, done) => {
  try {
    let user = await User.findOne({ googleId: profile.id });
    if (!user) {
      user = await User.create({
        googleId: profile.id,
        name: profile.displayName,
        email: profile.emails[0].value,
        avatar: profile.photos[0].value
      });
    }
    done(null, user);
  } catch (err) { done(err, null); }
}));

// Routes
app.get('/api/auth/google', passport.authenticate('google', { scope: ['profile', 'email'] }));
app.get('/api/auth/google/callback',
  passport.authenticate('google', { session: false }),
  (req, res) => {
    const token = generateToken(req.user._id, req.user.role);
    res.redirect(`${process.env.CLIENT_URL}/oauth-success?token=${token}`);
  }
);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 57. How do you protect routes in a MERN application?

```javascript
// ── Backend — Express route protection ──
// protect middleware (from Q52) verifies JWT
// restrictTo middleware (from Q53) checks role

app.get('/api/admin/stats', protect, restrictTo('admin'), getAdminStats);
app.get('/api/profile', protect, getMyProfile);
app.post('/api/posts', protect, createPost);

// ── Frontend — React route protection ──
function PrivateRoute({ children, requiredRole }) {
  const { user, isLoading } = useAuth();

  if (isLoading) return <Spinner />;
  if (!user) return <Navigate to="/login" replace />;
  if (requiredRole && user.role !== requiredRole) return <Navigate to="/403" replace />;

  return children;
}

// Usage in React Router
<Routes>
  <Route path="/dashboard" element={<PrivateRoute><Dashboard /></PrivateRoute>} />
  <Route path="/admin" element={<PrivateRoute requiredRole="admin"><AdminPanel /></PrivateRoute>} />
  <Route path="/login" element={<Login />} />
</Routes>
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Full Stack Integration

<br>

### 58. How does the React frontend communicate with the Express backend?

```
React (localhost:3000)
    ↓  HTTP Request (Axios/fetch)
    ↓  Headers: Authorization: Bearer <JWT>
    ↓  Body: { "title": "My Post", "content": "..." }
Express API (localhost:5000)
    ↓  Parses request (express.json middleware)
    ↓  Validates auth (protect middleware)
    ↓  Calls controller → Mongoose query
MongoDB
    ↓  Returns document
Express sends JSON response
    ↓  { success: true, data: { _id: "...", title: "..." } }
React updates state → re-renders UI
```

```javascript
// React service file — api/postsApi.js
import axios from 'axios';

const API = axios.create({ baseURL: process.env.REACT_APP_API_URL });

// Auto-attach token to every request
API.interceptors.request.use(config => {
  const token = localStorage.getItem('token');
  if (token) config.headers.Authorization = `Bearer ${token}`;
  return config;
});

export const fetchPosts = () => API.get('/posts');
export const createPost = (data) => API.post('/posts', data);
export const updatePost = (id, data) => API.patch(`/posts/${id}`, data);
export const deletePost = (id) => API.delete(`/posts/${id}`);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 59. What is Axios? How is it different from the fetch API?

| Feature | Axios | fetch API |
| ------- | ----- | --------- |
| Auto JSON parse | ✅ Automatic | ❌ Need `.json()` manually |
| Request/Response interceptors | ✅ Built-in | ❌ No |
| Error handling | ✅ Throws on 4xx/5xx | ❌ Only throws on network error |
| Request cancellation | ✅ `AbortController` + built-in | ✅ `AbortController` |
| Upload progress | ✅ Built-in | ❌ Manual |
| Browser support | ✅ All | Modern browsers only |
| Bundle size | ~14KB | Built-in (0KB) |

```javascript
// fetch API — more manual
const res = await fetch('/api/posts', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json', 'Authorization': `Bearer ${token}` },
  body: JSON.stringify(data)
});
if (!res.ok) throw new Error('Request failed'); // fetch doesn't throw on 4xx!
const result = await res.json();

// Axios — cleaner
const { data } = await axios.post('/api/posts', data, {
  headers: { Authorization: `Bearer ${token}` }
}); // auto-throws on 4xx/5xx, auto-parses JSON
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 60. How do you connect MongoDB to an Express app using Mongoose?

```javascript
// config/database.js
const mongoose = require('mongoose');

const connectDB = async () => {
  try {
    const conn = await mongoose.connect(process.env.MONGODB_URI, {
      // These are defaults in Mongoose 6+, included here for clarity
      // useNewUrlParser: true,
      // useUnifiedTopology: true
    });

    console.log(`✅ MongoDB connected: ${conn.connection.host}`);

    // Handle connection events
    mongoose.connection.on('error', err => console.error('MongoDB error:', err));
    mongoose.connection.on('disconnected', () => console.log('MongoDB disconnected'));

  } catch (error) {
    console.error('❌ MongoDB connection failed:', error.message);
    process.exit(1); // exit process on connection failure
  }
};

// Handle graceful shutdown
process.on('SIGINT', async () => {
  await mongoose.connection.close();
  console.log('MongoDB connection closed on app termination');
  process.exit(0);
});

module.exports = connectDB;

// server.js
require('dotenv').config();
const connectDB = require('./config/database');

connectDB(); // connect before starting server
app.listen(process.env.PORT || 5000, () => console.log('Server running'));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 61. What is a proxy in a MERN app development setup?

In development, React runs on port 3000 and Express on port 5000. A **proxy** tells the React dev server to forward API requests to the Express server — avoiding CORS issues during development.

```json
// package.json in React app (CRA)
{
  "proxy": "http://localhost:5000"
}
// Now: fetch('/api/users') → proxied to http://localhost:5000/api/users

// For Vite (vite.config.js)
export default {
  server: {
    proxy: {
      '/api': {
        target: 'http://localhost:5000',
        changeOrigin: true
      }
    }
  }
};
```

> **Note:** The proxy only works in development. In production, serve both from the same domain, or configure CORS properly in Express.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 62. What is WebSocket? When would you use it instead of REST in MERN?

WebSocket provides a **persistent, full-duplex communication channel** between client and server over a single TCP connection — enabling real-time bidirectional data flow.

| Feature | REST API | WebSocket |
| ------- | -------- | --------- |
| Connection | New connection per request | Persistent connection |
| Direction | Client → Server (request) | Both directions simultaneously |
| Real-time | ❌ Polling required | ✅ Instant push |
| Overhead | Headers on every request | Once on handshake |
| Use case | CRUD operations | Chat, live scores, notifications |

```javascript
// Server — Socket.IO (WebSocket library)
const { Server } = require('socket.io');
const io = new Server(httpServer, { cors: { origin: process.env.CLIENT_URL } });

io.on('connection', (socket) => {
  console.log('User connected:', socket.id);

  socket.on('join-room', (roomId) => socket.join(roomId));

  socket.on('send-message', async ({ roomId, message, userId }) => {
    const saved = await Message.create({ content: message, sender: userId, room: roomId });
    io.to(roomId).emit('new-message', saved); // broadcast to room
  });

  socket.on('disconnect', () => console.log('User disconnected:', socket.id));
});

// React client
import { io } from 'socket.io-client';
const socket = io(process.env.REACT_APP_API_URL);
socket.on('new-message', (message) => setMessages(prev => [...prev, message]));
socket.emit('send-message', { roomId, message: text, userId: user._id });
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 63. How do you handle file uploads in a MERN application?

```javascript
// Backend — Multer (disk storage)
const multer = require('multer');
const path = require('path');

const storage = multer.diskStorage({
  destination: (req, file, cb) => cb(null, 'uploads/'),
  filename: (req, file, cb) => {
    const uniqueName = `${Date.now()}-${Math.round(Math.random()*1e9)}${path.extname(file.originalname)}`;
    cb(null, uniqueName);
  }
});

const upload = multer({
  storage,
  limits: { fileSize: 5 * 1024 * 1024 }, // 5MB limit
  fileFilter: (req, file, cb) => {
    const allowedTypes = /jpeg|jpg|png|gif/;
    if (allowedTypes.test(file.mimetype)) cb(null, true);
    else cb(new Error('Only image files allowed'));
  }
});

// Route
app.post('/api/upload/avatar', protect, upload.single('avatar'), async (req, res) => {
  const user = await User.findByIdAndUpdate(req.user.id,
    { avatar: `/uploads/${req.file.filename}` },
    { new: true }
  );
  res.json({ avatarUrl: user.avatar });
});

// React — FormData
const handleUpload = async (file) => {
  const formData = new FormData();
  formData.append('avatar', file);
  const { data } = await axios.post('/api/upload/avatar', formData, {
    headers: { 'Content-Type': 'multipart/form-data' }
  });
  setAvatar(data.avatarUrl);
};
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 64. What is pagination and how do you implement it in MERN?

```javascript
// Backend — Mongoose pagination
const getPosts = asyncHandler(async (req, res) => {
  const page = parseInt(req.query.page) || 1;
  const limit = parseInt(req.query.limit) || 10;
  const skip = (page - 1) * limit;

  const [posts, total] = await Promise.all([
    Post.find({ isPublished: true })
      .populate('author', 'name avatar')
      .sort({ createdAt: -1 })
      .skip(skip)
      .limit(limit),
    Post.countDocuments({ isPublished: true })
  ]);

  res.json({
    posts,
    currentPage: page,
    totalPages: Math.ceil(total / limit),
    totalPosts: total,
    hasNextPage: page < Math.ceil(total / limit),
    hasPrevPage: page > 1
  });
});

// React — consuming paginated API
function PostList() {
  const [posts, setPosts] = useState([]);
  const [pagination, setPagination] = useState({});
  const [currentPage, setCurrentPage] = useState(1);

  useEffect(() => {
    axios.get(`/api/posts?page=${currentPage}&limit=10`)
      .then(({ data }) => { setPosts(data.posts); setPagination(data); });
  }, [currentPage]);

  return (
    <div>
      {posts.map(p => <PostCard key={p._id} post={p} />)}
      <div className="pagination">
        <button disabled={!pagination.hasPrevPage} onClick={() => setCurrentPage(p => p - 1)}>
          Previous
        </button>
        <span>Page {pagination.currentPage} of {pagination.totalPages}</span>
        <button disabled={!pagination.hasNextPage} onClick={() => setCurrentPage(p => p + 1)}>
          Next
        </button>
      </div>
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Architecture & Performance

<br>

### 65. What is MVC architecture? How does it apply to MERN?

MVC (Model-View-Controller) is a design pattern that **separates application concerns** into three distinct layers.

| Layer | MERN equivalent | Responsibility |
| ----- | --------------- | -------------- |
| **Model** | Mongoose Schema/Model | Data structure, DB interaction, business logic |
| **View** | React components | UI rendering, user interaction |
| **Controller** | Express route handlers | Request handling, calling models, sending responses |

```
React (View)  →  HTTP Request  →  Express Router  →  Controller  →  Mongoose Model  →  MongoDB
               ←  JSON Response ←                 ←             ←                   ←
```

```
backend/
├── models/          ← M: Mongoose schemas
│   ├── User.js
│   └── Post.js
├── controllers/     ← C: Business logic
│   ├── userController.js
│   └── postController.js
├── routes/          ← C: URL mapping
│   ├── userRoutes.js
│   └── postRoutes.js
frontend/
└── src/
    └── components/  ← V: React UI
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 66. How do you structure a large MERN project?

```
project-root/
├── backend/
│   ├── config/
│   │   ├── database.js       ← MongoDB connection
│   │   └── cloudinary.js     ← File storage config
│   ├── controllers/          ← Business logic per resource
│   │   ├── authController.js
│   │   ├── userController.js
│   │   └── postController.js
│   ├── middleware/
│   │   ├── auth.js           ← protect, restrictTo
│   │   ├── errorHandler.js   ← global error handler
│   │   ├── rateLimiter.js
│   │   └── upload.js         ← multer config
│   ├── models/               ← Mongoose schemas
│   │   ├── User.js
│   │   └── Post.js
│   ├── routes/               ← Express routers
│   │   ├── authRoutes.js
│   │   ├── userRoutes.js
│   │   └── postRoutes.js
│   ├── utils/
│   │   ├── sendEmail.js
│   │   ├── generateToken.js
│   │   └── apiFeatures.js    ← filtering, sorting, pagination helper
│   ├── validations/          ← Joi/express-validator schemas
│   ├── .env
│   ├── server.js             ← Entry point
│   └── package.json
├── frontend/
│   ├── public/
│   └── src/
│       ├── api/              ← Axios API service files
│       ├── components/       ← Reusable UI components
│       ├── features/         ← Feature modules (auth, posts, users)
│       ├── hooks/            ← Custom React hooks
│       ├── pages/            ← Route-level components
│       ├── store/            ← Redux/Zustand state
│       ├── utils/
│       └── App.jsx
└── package.json              ← Root (optional monorepo scripts)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 67. What is caching and how do you implement it in a MERN app?

Caching stores the result of expensive operations so subsequent requests can be served faster without hitting the database.

```javascript
// In-memory caching with node-cache (simple, single-server)
const NodeCache = require('node-cache');
const cache = new NodeCache({ stdTTL: 300, checkperiod: 60 }); // 5 min TTL

const getProducts = asyncHandler(async (req, res) => {
  const cacheKey = `products_${JSON.stringify(req.query)}`;

  // Check cache first
  const cached = cache.get(cacheKey);
  if (cached) return res.json({ source: 'cache', data: cached });

  // Cache miss — query DB
  const products = await Product.find(req.query).limit(50);
  cache.set(cacheKey, products); // store in cache

  res.json({ source: 'database', data: products });
});

// Cache invalidation on update
const updateProduct = asyncHandler(async (req, res) => {
  const product = await Product.findByIdAndUpdate(req.params.id, req.body, { new: true });
  cache.flushAll(); // clear all cache (or selectively by key)
  res.json(product);
});

// HTTP caching — set Cache-Control headers
app.get('/api/public/config', (req, res) => {
  res.set('Cache-Control', 'public, max-age=3600'); // browser caches for 1 hour
  res.json(publicConfig);
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 68. What is Redis and how is it used with MERN?

Redis is an **in-memory data structure store** used as a database, cache, and message broker. It's much faster than MongoDB for temporary or frequently-accessed data.

```javascript
// npm install redis ioredis
const redis = require('ioredis');
const client = new redis(process.env.REDIS_URL);

// Caching middleware
const cacheMiddleware = (ttl = 300) => async (req, res, next) => {
  const key = `cache:${req.originalUrl}`;
  const cached = await client.get(key);

  if (cached) return res.json(JSON.parse(cached));

  // Override res.json to also cache the response
  const originalJson = res.json.bind(res);
  res.json = async (data) => {
    await client.setex(key, ttl, JSON.stringify(data));
    return originalJson(data);
  };
  next();
};

app.get('/api/products', cacheMiddleware(600), getProducts);

// Session storage
await client.setex(`session:${userId}`, 3600, JSON.stringify(sessionData));
const session = JSON.parse(await client.get(`session:${userId}`));

// Rate limiting with Redis (distributed — works across multiple servers)
// Use redis-rate-limiter or express-rate-limit with RedisStore

// Pub/Sub for real-time features
const subscriber = new redis();
subscriber.subscribe('notifications');
subscriber.on('message', (channel, message) => {
  io.emit('notification', JSON.parse(message));
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 69. How do you optimize MongoDB query performance?

```javascript
// 1. Use indexes for frequently queried fields (covered in Q22)

// 2. Use .select() to fetch only needed fields (projection)
const users = await User.find().select('name email avatar'); // don't fetch password, etc.

// 3. Use .lean() for read-only queries (returns plain JS objects, not Mongoose docs)
const products = await Product.find().lean(); // 2-3x faster, less memory

// 4. Avoid fetching all documents — always use .limit()
const recent = await Post.find().sort({ createdAt: -1 }).limit(20);

// 5. Use aggregation pipeline instead of multiple queries
// ❌ N+1 — separate query per user
const users = await User.find();
const usersWithCount = await Promise.all(
  users.map(async user => ({
    ...user._doc,
    postCount: await Post.countDocuments({ author: user._id })
  }))
);

// ✅ Single aggregation query
const usersWithCount = await User.aggregate([
  { $lookup: { from: 'posts', localField: '_id', foreignField: 'author', as: 'posts' } },
  { $addFields: { postCount: { $size: '$posts' } } },
  { $project: { posts: 0 } } // remove array, keep count
]);

// 6. Use explain() to analyze query performance
const plan = await User.find({ email: 'test@test.com' }).explain('executionStats');
console.log(plan.executionStats.totalDocsExamined); // should be low with index
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 70. What is the N+1 query problem and how do you fix it in Mongoose?

The N+1 problem occurs when you run **1 query to get a list, then N additional queries** for each item in the list — causing massive database overhead.

```javascript
// ❌ N+1 Problem — 1 query for posts + 1 query per post for author
const posts = await Post.find(); // query 1
for (const post of posts) {
  post.authorData = await User.findById(post.author); // N more queries!
}
// Total: 1 + N queries (if 100 posts → 101 queries!)

// ✅ Fix 1: Use .populate() — Mongoose batches into 2 queries
const posts = await Post.find().populate('author', 'name avatar');
// Total: 2 queries (1 for posts, 1 for all referenced users IN)

// ✅ Fix 2: Use aggregation $lookup — single query
const posts = await Post.aggregate([
  { $lookup: {
    from: 'users',
    localField: 'author',
    foreignField: '_id',
    as: 'author',
    pipeline: [{ $project: { name: 1, avatar: 1 } }]
  }},
  { $unwind: '$author' }
]);
// Total: 1 query
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 71. How do you handle large file storage in MERN? What is GridFS?

For files larger than 16MB (MongoDB's BSON document limit), use **GridFS** or external cloud storage.

```javascript
// Option 1: GridFS (MongoDB's built-in large file storage)
// Splits files into 255KB chunks, stores in "fs.files" + "fs.chunks" collections
const mongoose = require('mongoose');
const { GridFSBucket } = require('mongodb');

let gfs;
mongoose.connection.once('open', () => {
  gfs = new GridFSBucket(mongoose.connection.db, { bucketName: 'uploads' });
});

// Upload to GridFS
app.post('/upload', upload.single('file'), (req, res) => {
  const uploadStream = gfs.openUploadStream(req.file.originalname);
  fs.createReadStream(req.file.path).pipe(uploadStream);
  uploadStream.on('finish', () => res.json({ fileId: uploadStream.id }));
});

// Option 2: Cloudinary (recommended for images/videos)
const cloudinary = require('cloudinary').v2;
cloudinary.config({ cloud_name, api_key, api_secret });

const result = await cloudinary.uploader.upload(req.file.path, {
  folder: 'webortex/avatars',
  transformation: [{ width: 400, height: 400, crop: 'fill' }]
});
const imageUrl = result.secure_url; // store this URL in MongoDB

// Option 3: AWS S3
const { S3Client, PutObjectCommand } = require('@aws-sdk/client-s3');
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 72. What is GraphQL? When would you use it instead of REST in MERN?

GraphQL is a **query language for APIs** that lets clients request exactly the data they need — no more, no less.

| Feature | REST API | GraphQL |
| ------- | -------- | ------- |
| Endpoints | Multiple (`/users`, `/posts`) | Single (`/graphql`) |
| Over-fetching | ✅ Common | ❌ Client specifies exact fields |
| Under-fetching | ✅ Need multiple requests | ❌ Single query for nested data |
| Versioning | `/v1/`, `/v2/` | Schema evolution |
| Learning curve | Low | Higher |
| Best for | Simple CRUD apps | Complex data, mobile apps |

```javascript
// GraphQL query vs REST
// REST: GET /api/users/1 → returns ALL user fields
// REST: GET /api/users/1/posts → separate request

// GraphQL: single query, exact fields
const query = `
  query {
    user(id: "1") {
      name
      email
      posts {
        title
        createdAt
      }
    }
  }
`;
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — DevOps & Deployment

<br>

### 73. How do you deploy a MERN application?

```
Deployment options:

Frontend (React):
├── Vercel (recommended — zero config, auto-deploys from GitHub)
├── Netlify
└── AWS S3 + CloudFront

Backend (Node/Express):
├── Render (free tier available, easy setup)
├── Railway
├── AWS EC2 (full control)
├── Heroku
└── DigitalOcean App Platform

Database (MongoDB):
└── MongoDB Atlas (managed cloud — recommended)
```

```bash
# Full-stack on Render (most common for MERN beginners)

# 1. Push code to GitHub
# 2. Create MongoDB Atlas cluster, get connection string
# 3. Create Render Web Service (backend)
#    - Build command: npm install
#    - Start command: node server.js
#    - Add env vars: MONGODB_URI, JWT_SECRET, etc.
# 4. Create Vercel project (frontend)
#    - Set REACT_APP_API_URL=https://your-render-app.onrender.com
# 5. Done!

# Build React for production (before deploying frontend)
npm run build
# Creates /build folder with optimized static files
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 74. What is Docker and how is it used in MERN deployment?

Docker **packages your application and all its dependencies** into a standardized container — ensuring it runs consistently across any environment ("works on my machine" problem solved).

```dockerfile
# backend/Dockerfile
FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm ci --only=production

COPY . .

EXPOSE 5000
CMD ["node", "server.js"]
```

```yaml
# docker-compose.yml — run entire MERN stack with one command
version: '3.8'
services:
  mongodb:
    image: mongo:6
    environment:
      MONGO_INITDB_ROOT_USERNAME: admin
      MONGO_INITDB_ROOT_PASSWORD: password
    volumes:
      - mongo-data:/data/db
    ports:
      - "27017:27017"

  backend:
    build: ./backend
    ports:
      - "5000:5000"
    environment:
      MONGODB_URI: mongodb://admin:password@mongodb:27017/mydb
      JWT_SECRET: supersecret
    depends_on:
      - mongodb

  frontend:
    build: ./frontend
    ports:
      - "3000:3000"
    depends_on:
      - backend

volumes:
  mongo-data:
```

```bash
docker-compose up -d  # start all services
docker-compose down   # stop all services
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 75. What is CI/CD? How do you set it up for a MERN project?

CI/CD (Continuous Integration / Continuous Deployment) **automates testing and deployment** — every push to main triggers tests, then automatic deployment.

```yaml
# .github/workflows/deploy.yml — GitHub Actions
name: Deploy MERN App

on:
  push:
    branches: [main]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with: { node-version: '18' }
      - name: Install backend deps
        run: cd backend && npm ci
      - name: Run backend tests
        run: cd backend && npm test
        env:
          MONGODB_URI: ${{ secrets.MONGODB_URI_TEST }}
          JWT_SECRET: ${{ secrets.JWT_SECRET }}

  deploy-backend:
    needs: test
    runs-on: ubuntu-latest
    steps:
      - name: Deploy to Render
        run: curl -X POST ${{ secrets.RENDER_DEPLOY_HOOK }}

  deploy-frontend:
    needs: test
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Deploy to Vercel
        uses: amondnet/vercel-action@v25
        with:
          vercel-token: ${{ secrets.VERCEL_TOKEN }}
          vercel-org-id: ${{ secrets.VERCEL_ORG_ID }}
          vercel-project-id: ${{ secrets.VERCEL_PROJECT_ID }}
          vercel-args: '--prod'
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 76. What is NGINX and why is it used with MERN apps?

NGINX is a **high-performance web server and reverse proxy** commonly used in MERN deployments to route traffic, serve static files, and handle SSL.

```nginx
# /etc/nginx/sites-available/myapp
server {
  listen 80;
  server_name yourdomain.com www.yourdomain.com;
  return 301 https://$server_name$request_uri; # redirect to HTTPS
}

server {
  listen 443 ssl;
  server_name yourdomain.com;

  ssl_certificate /etc/letsencrypt/live/yourdomain.com/fullchain.pem;
  ssl_certificate_key /etc/letsencrypt/live/yourdomain.com/privkey.pem;

  # Serve React static files
  location / {
    root /var/www/myapp/frontend/build;
    index index.html;
    try_files $uri $uri/ /index.html; # SPA fallback
  }

  # Proxy API requests to Express
  location /api/ {
    proxy_pass http://localhost:5000;
    proxy_http_version 1.1;
    proxy_set_header Upgrade $http_upgrade;
    proxy_set_header Connection 'upgrade';
    proxy_set_header Host $host;
    proxy_cache_bypass $http_upgrade;
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 77. How do you scale a MERN application?

```
Scaling strategies by layer:

MongoDB (Database Layer):
├── Vertical scaling (bigger server) → up to a point
├── Replica Sets → read replicas for read-heavy apps
└── Sharding → distribute data across multiple servers

Node.js/Express (Application Layer):
├── PM2 clustering → use all CPU cores: pm2 start server.js -i max
├── Horizontal scaling → multiple server instances + load balancer
└── Microservices → split into smaller independent services

React (Frontend Layer):
├── CDN → serve static assets from global edge nodes
├── Code splitting → load-on-demand with React.lazy
└── Asset optimization → image compression, minification

Caching Layer:
├── Redis → cache DB queries, sessions, rate limiting
└── HTTP caching headers → browser + CDN caching

Infrastructure:
├── Load Balancer (NGINX, AWS ALB) → distribute traffic across instances
└── Auto-scaling → AWS Auto Scaling / Kubernetes → add servers under load
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Testing & Security

<br>

### 78. How do you test a MERN application?

| Layer | Tool | Purpose |
| ----- | ---- | ------- |
| Backend unit | Jest | Test utility functions, helpers |
| Backend API | Jest + Supertest | Test Express routes end-to-end |
| Frontend unit | Jest | Test utility functions, hooks |
| Frontend component | React Testing Library | Test component behaviour |
| E2E | Playwright / Cypress | Test full user flows in browser |
| API manual | Postman | Manual API testing during development |

```bash
# Install testing dependencies
npm install --save-dev jest supertest @testing-library/react
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 79. How do you write unit tests for an Express API?

```javascript
// __tests__/auth.test.js
const request = require('supertest');
const mongoose = require('mongoose');
const app = require('../app'); // export app separately from server.js
const User = require('../models/User');

beforeAll(async () => {
  await mongoose.connect(process.env.MONGODB_URI_TEST);
});

afterEach(async () => {
  await User.deleteMany({}); // clean up after each test
});

afterAll(async () => {
  await mongoose.connection.close();
});

describe('POST /api/auth/register', () => {
  test('should register a new user and return token', async () => {
    const res = await request(app)
      .post('/api/auth/register')
      .send({ name: 'Sisi', email: 'sisi@test.com', password: 'password123' });

    expect(res.statusCode).toBe(201);
    expect(res.body).toHaveProperty('token');
    expect(res.body.user.email).toBe('sisi@test.com');
    expect(res.body.user).not.toHaveProperty('password');
  });

  test('should return 409 if email already exists', async () => {
    await User.create({ name: 'Sisi', email: 'sisi@test.com', password: 'pass123' });

    const res = await request(app)
      .post('/api/auth/register')
      .send({ name: 'Sisi', email: 'sisi@test.com', password: 'pass123' });

    expect(res.statusCode).toBe(409);
    expect(res.body.message).toMatch(/email already in use/i);
  });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 80. What are common security vulnerabilities in MERN apps and how do you prevent them?

| Vulnerability | Risk | Prevention |
| ------------- | ---- | ---------- |
| **XSS** | Malicious scripts execute in browser | React escapes by default; sanitize `dangerouslySetInnerHTML` |
| **NoSQL Injection** | Malicious operators in MongoDB queries | Sanitize with `express-mongo-sanitize` |
| **JWT in localStorage** | Stolen by XSS | Use HTTP-only cookies instead |
| **Brute force login** | Password cracking | Rate limiting on auth routes |
| **CSRF** | Unauthorized requests from other sites | `SameSite` cookie, CSRF tokens |
| **Unprotected routes** | Unauthorized data access | `protect` + `restrictTo` middleware |
| **Sensitive data exposure** | Leaking passwords, keys in responses | `select: false` on password field |
| **Insecure dependencies** | Known CVEs in npm packages | `npm audit` regularly |
| **Missing security headers** | Various browser-based attacks | `helmet` middleware |
| **DoS attacks** | Server overwhelmed by requests | Rate limiting, load balancing |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 81. What is Helmet.js and why is it used?

Helmet.js is an Express middleware that **sets various HTTP security headers** to protect against well-known browser vulnerabilities.

```javascript
const helmet = require('helmet');

app.use(helmet()); // sets all headers with sensible defaults

// What helmet sets:
// Content-Security-Policy     → prevents XSS, clickjacking
// X-Frame-Options: DENY       → prevents iframe embedding (clickjacking)
// X-Content-Type-Options      → prevents MIME sniffing
// Referrer-Policy             → controls referrer information
// Strict-Transport-Security   → forces HTTPS
// X-XSS-Protection            → legacy XSS filter

// Customize specific headers
app.use(helmet({
  contentSecurityPolicy: {
    directives: {
      defaultSrc: ["'self'"],
      scriptSrc: ["'self'", "https://cdn.jsdelivr.net"],
      imgSrc: ["'self'", "data:", "https://res.cloudinary.com"]
    }
  },
  crossOriginEmbedderPolicy: false // disable if using external iframes
}));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 82. What is input sanitization and how do you implement it?

Input sanitization **strips or escapes dangerous characters/operators** from user input before using it in queries or rendering.

```javascript
// 1. Sanitize MongoDB operators to prevent NoSQL injection
const mongoSanitize = require('express-mongo-sanitize');
app.use(mongoSanitize());
// Removes $ and . from req.body, req.query, req.params
// { "email": { "$gt": "" } } → blocked (NoSQL injection attempt)

// 2. Sanitize HTML to prevent XSS in stored content
const createDOMPurify = require('dompurify');
const { JSDOM } = require('jsdom');
const DOMPurify = createDOMPurify(new JSDOM('').window);

postSchema.pre('save', function(next) {
  if (this.content) {
    this.content = DOMPurify.sanitize(this.content); // strip malicious HTML
  }
  next();
});

// 3. Validate and sanitize with express-validator
const { body, validationResult } = require('express-validator');

const validateRegister = [
  body('name').trim().escape().isLength({ min: 2 }),
  body('email').trim().normalizeEmail().isEmail(),
  body('password').isLength({ min: 8 }),
  (req, res, next) => {
    const errors = validationResult(req);
    if (!errors.isEmpty()) return res.status(400).json({ errors: errors.array() });
    next();
  }
];

app.post('/api/auth/register', validateRegister, register);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🎯 Scenario & Conceptual Questions (MNC Favourites)

<br>

### 83. How would you design a real-time chat application using MERN?

```
Architecture:

MongoDB: messages, rooms, users collections
Express: REST API (auth, get message history) + Socket.IO server
React: UI with socket.io-client
Redis: online users, typing indicators (fast ephemeral data)

Key schema:
Message { content, sender: ref(User), room: ref(Room), createdAt, readBy: [ref(User)] }
Room    { name, participants: [ref(User)], isGroup, lastMessage }

Socket events:
→ join-room     (client joins a room)
→ send-message  (client sends a message)
← new-message   (server broadcasts to room)
→ typing        (client is typing)
← user-typing   (server broadcasts typing indicator)
→ mark-read     (client marks messages as read)
← messages-read (server notifies sender)
```

```javascript
// Key implementation highlights:
io.on('connection', (socket) => {
  // Auth: verify JWT on connection
  const user = verifyToken(socket.handshake.auth.token);
  socket.userId = user.id;

  socket.on('join-room', (roomId) => {
    socket.join(roomId);
    socket.to(roomId).emit('user-joined', { userId: user.id });
  });

  socket.on('send-message', async ({ roomId, content }) => {
    const message = await Message.create({ content, sender: user.id, room: roomId });
    const populated = await message.populate('sender', 'name avatar');
    io.to(roomId).emit('new-message', populated); // broadcast to all in room
    await Room.findByIdAndUpdate(roomId, { lastMessage: message._id });
  });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 84. How would you implement role-based access control (RBAC) in MERN?

```javascript
// Roles: admin > editor > user

// 1. Store role in User model
const userSchema = new mongoose.Schema({
  role: { type: String, enum: ['user', 'editor', 'admin'], default: 'user' }
});

// 2. Role middleware (generic)
const restrictTo = (...roles) => (req, res, next) => {
  if (!roles.includes(req.user.role)) {
    return res.status(403).json({ message: `Role '${req.user.role}' is not authorized` });
  }
  next();
};

// 3. Resource ownership check
const checkOwnership = (Model) => asyncHandler(async (req, res, next) => {
  const resource = await Model.findById(req.params.id);
  if (!resource) return res.status(404).json({ message: 'Resource not found' });
  if (resource.author.toString() !== req.user.id && req.user.role !== 'admin') {
    return res.status(403).json({ message: 'Not authorized to modify this resource' });
  }
  req.resource = resource;
  next();
});

// 4. Apply to routes
router.get('/', protect, getAllPosts);           // any logged-in user
router.post('/', protect, restrictTo('editor', 'admin'), createPost);
router.patch('/:id', protect, checkOwnership(Post), updatePost); // owner or admin
router.delete('/:id', protect, restrictTo('admin'), deletePost); // admin only

// 5. React — hide UI elements based on role
const { user } = useAuth();
{user.role === 'admin' && <AdminDashboard />}
{['editor', 'admin'].includes(user.role) && <CreatePostButton />}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 85. How do you handle API versioning in Express.js?

```javascript
// Option 1: URL path versioning (most common)
app.use('/api/v1/users', require('./routes/v1/userRoutes'));
app.use('/api/v2/users', require('./routes/v2/userRoutes'));

// Option 2: Query parameter versioning
app.get('/api/users', (req, res) => {
  const version = req.query.version || 'v1';
  if (version === 'v2') return res.json(usersV2Format);
  res.json(usersV1Format);
});

// Option 3: Header versioning
app.get('/api/users', (req, res) => {
  const version = req.headers['api-version'] || '1';
  const handler = version === '2' ? getUsersV2 : getUsersV1;
  handler(req, res);
});

// Best practice for versioning:
// - Keep v1 routes working when releasing v2 (backward compatibility)
// - Document breaking changes clearly
// - Deprecate old versions with warnings in responses
// - Use URL versioning for public APIs (most explicit and cacheable)

// Deprecation warning middleware
app.use('/api/v1', (req, res, next) => {
  res.setHeader('Deprecation', 'true');
  res.setHeader('Sunset', 'Sat, 31 Dec 2025 23:59:59 GMT');
  next();
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 86. How would you implement a search feature in a MERN app?

```javascript
// Backend — MongoDB text search
// 1. Create text index
productSchema.index({ name: 'text', description: 'text', category: 'text' });

// 2. Full-text search route
app.get('/api/search', asyncHandler(async (req, res) => {
  const { q, category, minPrice, maxPrice, sort, page = 1, limit = 12 } = req.query;

  const query = {};

  if (q) query.$text = { $search: q };                   // full-text search
  if (category) query.category = category;               // filter
  if (minPrice || maxPrice) {
    query.price = {};
    if (minPrice) query.price.$gte = Number(minPrice);
    if (maxPrice) query.price.$lte = Number(maxPrice);
  }

  const sortOptions = {
    relevance: q ? { score: { $meta: 'textScore' } } : { createdAt: -1 },
    price_asc: { price: 1 },
    price_desc: { price: -1 },
    newest: { createdAt: -1 }
  };

  const products = await Product.find(
    query,
    q ? { score: { $meta: 'textScore' } } : {}         // include relevance score
  )
    .sort(sortOptions[sort] || sortOptions.newest)
    .skip((page - 1) * limit)
    .limit(Number(limit))
    .lean();

  res.json({ products, total: await Product.countDocuments(query) });
}));

// React — debounced search
function SearchBar() {
  const [query, setQuery] = useState('');
  const debouncedQuery = useDebounce(query, 400); // custom hook

  useEffect(() => {
    if (debouncedQuery) fetchResults(debouncedQuery);
  }, [debouncedQuery]);

  return <input value={query} onChange={e => setQuery(e.target.value)} />;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 87. What is SSR and when would you use it in a MERN app?

**SSR (Server-Side Rendering):** HTML is generated on the server and sent to the browser — instead of sending an empty HTML shell and letting React render it on the client.

| Use SSR when | Use CSR (default React) when |
| ------------ | --------------------------- |
| SEO is critical (blogs, e-commerce, marketing sites) | Internal dashboards/tools (no SEO needed) |
| Fast first paint matters (poor network users) | Heavy user interaction after initial load |
| Social media preview cards (Open Graph meta tags) | Authenticated-only apps |
| Content marketing, landing pages | Admin panels, SaaS apps |

```
// In MERN: add Next.js as the React framework for SSR

// pages/products/[id].js (Next.js)
export async function getServerSideProps({ params }) {
  // This runs on the SERVER for every request
  const product = await fetch(`${process.env.API_URL}/api/products/${params.id}`)
    .then(r => r.json());
  return { props: { product } };
}

export default function ProductPage({ product }) {
  return (
    <div>
      <Head>
        <title>{product.name} | MyShop</title>
        <meta name="description" content={product.description} />
        {/* SEO meta tags populated with real data */}
      </Head>
      <ProductDetail product={product} />
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 88. How do you handle errors globally in a MERN application?

```javascript
// ── Backend: Centralized error handling ──

// utils/AppError.js
class AppError extends Error {
  constructor(message, statusCode) {
    super(message);
    this.statusCode = statusCode;
    this.status = String(statusCode).startsWith('4') ? 'fail' : 'error';
    this.isOperational = true;
    Error.captureStackTrace(this, this.constructor);
  }
}

// middleware/errorHandler.js
module.exports = (err, req, res, next) => {
  let error = { ...err, message: err.message };

  // MongoDB bad ObjectId
  if (err.name === 'CastError') error = new AppError(`Invalid ${err.path}: ${err.value}`, 400);
  // MongoDB duplicate key
  if (err.code === 11000) error = new AppError(`Duplicate value: ${JSON.stringify(err.keyValue)}`, 409);
  // Mongoose validation error
  if (err.name === 'ValidationError') {
    const message = Object.values(err.errors).map(e => e.message).join('. ');
    error = new AppError(message, 400);
  }
  // JWT errors
  if (err.name === 'JsonWebTokenError') error = new AppError('Invalid token', 401);
  if (err.name === 'TokenExpiredError') error = new AppError('Token expired, please login again', 401);

  res.status(error.statusCode || 500).json({
    status: error.status || 'error',
    message: error.message || 'Internal server error',
    ...(process.env.NODE_ENV === 'development' && { stack: err.stack })
  });
};

// ── Frontend: Global Axios error interceptor ──
axios.interceptors.response.use(
  response => response,
  async (error) => {
    if (error.response?.status === 401) {
      // Token expired — redirect to login
      localStorage.removeItem('token');
      window.location.href = '/login';
    }
    return Promise.reject(error.response?.data || error);
  }
);

// React Error Boundary for unhandled component errors
<ErrorBoundary fallback={<ErrorPage />}>
  <App />
</ErrorBoundary>
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 89. How would you implement refresh token rotation in a MERN app?

```javascript
// Two-token system:
// Access token (short-lived: 15min) — stored in memory/state
// Refresh token (long-lived: 7 days) — stored in HTTP-only cookie

// On Login
const accessToken = generateToken(user._id, '15m');
const refreshToken = generateToken(user._id, '7d');

// Store refresh token hash in DB
user.refreshToken = crypto.createHash('sha256').update(refreshToken).digest('hex');
await user.save();

// Send refresh token as HTTP-only cookie
res.cookie('refreshToken', refreshToken, { httpOnly: true, secure: true, maxAge: 7 * 24 * 60 * 60 * 1000 });
res.json({ accessToken }); // access token to memory/state only

// Refresh token endpoint
app.post('/api/auth/refresh', async (req, res) => {
  const { refreshToken } = req.cookies;
  if (!refreshToken) return res.status(401).json({ message: 'No refresh token' });

  const decoded = jwt.verify(refreshToken, process.env.JWT_SECRET);
  const tokenHash = crypto.createHash('sha256').update(refreshToken).digest('hex');
  const user = await User.findOne({ _id: decoded.userId, refreshToken: tokenHash });

  if (!user) return res.status(401).json({ message: 'Invalid refresh token' });

  // Rotation: invalidate old, issue new
  const newRefreshToken = generateToken(user._id, '7d');
  user.refreshToken = crypto.createHash('sha256').update(newRefreshToken).digest('hex');
  await user.save();

  res.cookie('refreshToken', newRefreshToken, { httpOnly: true, secure: true, maxAge: 7 * 24 * 60 * 60 * 1000 });
  res.json({ accessToken: generateToken(user._id, '15m') });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 90. What is microservices architecture? How does it differ from monolithic MERN?

| Feature | Monolithic MERN | Microservices |
| ------- | --------------- | ------------- |
| Structure | Single codebase, single server | Multiple independent services |
| Deployment | Deploy everything together | Deploy each service independently |
| Scaling | Scale entire app | Scale only bottleneck services |
| Technology | Same stack throughout | Each service can use different tech |
| Complexity | Low | High (service discovery, API gateway, IPC) |
| Best for | Startups, small-medium apps | Large teams, complex domains |
| Failure isolation | ❌ One bug can crash everything | ✅ Isolated failures |

```
Monolithic MERN:
[React] → [Single Express Server] → [MongoDB]

Microservices MERN:
[React]
   ↓
[API Gateway (Express/NGINX)]
   ↓ ↓ ↓ ↓
[Auth Service] [User Service] [Product Service] [Order Service]
   ↓                ↓               ↓                ↓
[Auth DB]      [User DB]       [Product DB]     [Order DB]

Communication: REST, gRPC, or message queues (RabbitMQ, Kafka)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 91. How do you implement email verification in a MERN app?

```javascript
// 1. On register — generate token, save to user, send email
const register = asyncHandler(async (req, res) => {
  const user = await User.create({ ...req.body, isVerified: false });

  const verifyToken = crypto.randomBytes(32).toString('hex');
  user.emailVerifyToken = crypto.createHash('sha256').update(verifyToken).digest('hex');
  user.emailVerifyExpires = Date.now() + 24 * 60 * 60 * 1000; // 24 hours
  await user.save();

  const verifyURL = `${process.env.CLIENT_URL}/verify-email/${verifyToken}`;
  await sendEmail({
    to: user.email,
    subject: 'Verify your email',
    html: `<p>Click <a href="${verifyURL}">here</a> to verify. Expires in 24h.</p>`
  });

  res.status(201).json({ message: 'Registration successful. Check your email.' });
});

// 2. Verify token endpoint
app.get('/api/auth/verify-email/:token', asyncHandler(async (req, res) => {
  const tokenHash = crypto.createHash('sha256').update(req.params.token).digest('hex');
  const user = await User.findOne({
    emailVerifyToken: tokenHash,
    emailVerifyExpires: { $gt: Date.now() }
  });

  if (!user) return res.status(400).json({ message: 'Token invalid or expired' });

  user.isVerified = true;
  user.emailVerifyToken = undefined;
  user.emailVerifyExpires = undefined;
  await user.save();

  res.json({ message: 'Email verified successfully!' });
}));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 92. How would you implement infinite scroll in a MERN app?

```javascript
// Backend — cursor-based pagination (better than page-based for infinite scroll)
app.get('/api/posts/feed', protect, asyncHandler(async (req, res) => {
  const { cursor, limit = 10 } = req.query;

  const query = {};
  if (cursor) query._id = { $lt: cursor }; // posts older than the last loaded post

  const posts = await Post
    .find(query)
    .sort({ _id: -1 }) // newest first
    .limit(Number(limit) + 1); // fetch one extra to check hasMore

  const hasMore = posts.length > limit;
  const data = hasMore ? posts.slice(0, -1) : posts;
  const nextCursor = data.length > 0 ? data[data.length - 1]._id : null;

  res.json({ posts: data, nextCursor, hasMore });
}));

// React — IntersectionObserver for infinite scroll
function Feed() {
  const [posts, setPosts] = useState([]);
  const [cursor, setCursor] = useState(null);
  const [hasMore, setHasMore] = useState(true);
  const loaderRef = useRef(null);

  const loadMore = async () => {
    const { data } = await axios.get(`/api/posts/feed?cursor=${cursor}&limit=10`);
    setPosts(prev => [...prev, ...data.posts]);
    setCursor(data.nextCursor);
    setHasMore(data.hasMore);
  };

  useEffect(() => {
    const observer = new IntersectionObserver(entries => {
      if (entries[0].isIntersecting && hasMore) loadMore();
    });
    if (loaderRef.current) observer.observe(loaderRef.current);
    return () => observer.disconnect();
  }, [cursor, hasMore]);

  return (
    <div>
      {posts.map(p => <PostCard key={p._id} post={p} />)}
      <div ref={loaderRef}>{hasMore ? <Spinner /> : <p>No more posts</p>}</div>
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 93. What is the difference between monorepo and polyrepo in a MERN project?

| Feature | Monorepo | Polyrepo |
| ------- | -------- | -------- |
| Structure | Frontend + Backend in **one** repository | Separate repositories per service |
| Shared code | ✅ Easy (shared `utils/`, `types/`) | ❌ Need npm packages or git submodules |
| Deployment | Can deploy together or separately | Independent deployments |
| Tooling | Turborepo, Nx, npm workspaces | Individual per repo |
| Complexity | Simple for small teams | Better for large teams with clear ownership |

```
Monorepo structure:
my-mern-app/
├── packages/
│   ├── frontend/   (React app)
│   ├── backend/    (Express server)
│   └── shared/     (TypeScript types, utils shared by both)
├── package.json    (workspaces: ["packages/*"])
└── turbo.json      (Turborepo config)

// package.json
{
  "workspaces": ["packages/*"],
  "scripts": {
    "dev": "turbo run dev",
    "build": "turbo run build",
    "test": "turbo run test"
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 94. How do you manage API keys and secrets securely in MERN?

```bash
# ── Rule #1: NEVER commit secrets to git ──
echo ".env" >> .gitignore
echo ".env.local" >> .gitignore
echo ".env.production" >> .gitignore

# .env.example — commit this (no real values!)
NODE_ENV=development
PORT=5000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/<dbname>
JWT_SECRET=<your-secret-here>
CLOUDINARY_API_KEY=<your-key>
```

```javascript
// ── Rule #2: Validate required env vars on startup ──
const requiredEnvVars = ['MONGODB_URI', 'JWT_SECRET', 'PORT'];
requiredEnvVars.forEach(key => {
  if (!process.env[key]) {
    console.error(`❌ Missing required env var: ${key}`);
    process.exit(1);
  }
});

// ── Rule #3: Never expose secrets to frontend ──
// React env vars prefixed with REACT_APP_ are bundled into JS (publicly visible!)
// REACT_APP_API_URL=https://api.myapp.com ← OK (public URL)
// REACT_APP_STRIPE_PUBLISHABLE_KEY=pk_... ← OK (publishable key is meant to be public)
// REACT_APP_JWT_SECRET=secret123 ← ❌ NEVER! Exposed in browser

// ── Rule #4: Use secret management in production ──
// AWS Secrets Manager, HashiCorp Vault, Doppler, Vercel/Render env var settings
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 95. What is the difference between horizontal and vertical scaling in MERN?

| Type | Description | How | Cost |
| ---- | ----------- | --- | ---- |
| **Vertical** (Scale Up) | Add more power to existing server | Bigger CPU, more RAM, faster disk | Expensive, has limits |
| **Horizontal** (Scale Out) | Add more servers, distribute load | Load balancer + multiple instances | Cheaper, unlimited in theory |

```
Vertical Scaling:
Single Server ── upgrade ──▶ Bigger Single Server
(2 CPU, 4GB RAM)             (32 CPU, 128GB RAM)
Problem: Still a single point of failure, expensive, has physical limits

Horizontal Scaling:
                     ┌─ Server 1 (Node.js)
Load Balancer ───────┤─ Server 2 (Node.js)
(NGINX/AWS ALB)      └─ Server 3 (Node.js)
                           ↓
                     MongoDB Atlas (scales separately)
                     Redis Cluster (scales separately)

MERN horizontal scaling checklist:
✅ Stateless Express server (no in-memory sessions)
✅ Sessions stored in Redis (shared across instances)
✅ File uploads → Cloudinary/S3 (not local disk)
✅ PM2 or Docker + Kubernetes for process management
✅ MongoDB Atlas for auto-scaling DB
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 96. How would you implement a notification system in a MERN app?

```javascript
// Notification types: in-app, email, push

// 1. Notification model
const notificationSchema = new mongoose.Schema({
  recipient: { type: ObjectId, ref: 'User', required: true },
  sender: { type: ObjectId, ref: 'User' },
  type: { type: String, enum: ['like', 'comment', 'follow', 'mention', 'system'] },
  message: String,
  link: String,    // URL to navigate to
  isRead: { type: Boolean, default: false }
}, { timestamps: true });

notificationSchema.index({ recipient: 1, isRead: 1 }); // for fast queries

// 2. Create and emit notification
const notify = async (recipientId, senderId, type, message, link) => {
  const notification = await Notification.create({
    recipient: recipientId, sender: senderId, type, message, link
  });
  // Real-time push via Socket.IO
  io.to(`user:${recipientId}`).emit('notification', notification);
  return notification;
};

// 3. Socket.IO — join personal room on connect
io.on('connection', (socket) => {
  const user = verifyToken(socket.handshake.auth.token);
  socket.join(`user:${user.id}`); // each user has their own room
});

// 4. Notification routes
app.get('/api/notifications', protect, async (req, res) => {
  const notifications = await Notification.find({ recipient: req.user.id })
    .populate('sender', 'name avatar')
    .sort({ createdAt: -1 }).limit(20);
  const unreadCount = await Notification.countDocuments({ recipient: req.user.id, isRead: false });
  res.json({ notifications, unreadCount });
});

app.patch('/api/notifications/read-all', protect, async (req, res) => {
  await Notification.updateMany({ recipient: req.user.id }, { isRead: true });
  res.json({ message: 'All notifications marked as read' });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 97. How do you handle CORS errors in a MERN app?

```javascript
// The error: "Access to XMLHttpRequest at 'http://localhost:5000/api/...' from origin
// 'http://localhost:3000' has been blocked by CORS policy"

// ── Solution 1: cors middleware in Express (recommended) ──
const cors = require('cors');

const corsOptions = {
  origin: (origin, callback) => {
    const allowedOrigins = [
      'http://localhost:3000',
      'https://yourapp.com',
      process.env.CLIENT_URL
    ];
    if (!origin || allowedOrigins.includes(origin)) {
      callback(null, true);
    } else {
      callback(new Error(`CORS not allowed for origin: ${origin}`));
    }
  },
  credentials: true,            // allow cookies
  methods: ['GET','POST','PUT','PATCH','DELETE','OPTIONS'],
  allowedHeaders: ['Content-Type', 'Authorization']
};
app.use(cors(corsOptions));
app.options('*', cors(corsOptions)); // preflight for all routes

// ── Solution 2: Development proxy (React side) ──
// In package.json: "proxy": "http://localhost:5000"
// React dev server forwards /api/* to localhost:5000

// ── Common mistakes ──
// ❌ Don't use app.use(cors()) with no options in production (allows ALL origins)
// ❌ Credentials: true requires a specific origin (not *)
// ❌ Missing app.options('*', cors()) blocks preflight requests
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 98. What is the difference between PUT and PATCH in REST APIs?

| Method | Operation | Idempotent | Sends |
| ------ | --------- | ---------- | ----- |
| **PUT** | Replace entire resource | ✅ Yes | Full document |
| **PATCH** | Partial update | ✅ Yes | Only changed fields |

```javascript
// User: { name: "Sisi", email: "s@s.com", role: "user", age: 20 }

// PUT — replace entire document (must send ALL fields)
// PUT /api/users/123
// Body: { "name": "Sisi Updated", "email": "s@s.com", "role": "user", "age": 20 }
// If you omit "age", it becomes null/undefined in the document!

// PATCH — update only what you send
// PATCH /api/users/123
// Body: { "name": "Sisi Updated" }
// Result: only name changes, everything else stays

// Express implementation
router.put('/:id', asyncHandler(async (req, res) => {
  // Replace entire document (validate all required fields are present)
  const user = await User.findByIdAndUpdate(req.params.id, req.body, {
    new: true, overwrite: true, runValidators: true
  });
  res.json(user);
}));

router.patch('/:id', asyncHandler(async (req, res) => {
  // Partial update (only update provided fields)
  const user = await User.findByIdAndUpdate(
    req.params.id,
    { $set: req.body }, // $set only updates provided fields
    { new: true, runValidators: true }
  );
  res.json(user);
}));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 99. How would you implement soft delete in MongoDB?

Soft delete marks a document as deleted **without actually removing it from the database** — useful for audit trails, recovery, or analytics.

```javascript
// Add deleted flag to schema
const postSchema = new mongoose.Schema({
  title: String,
  content: String,
  author: { type: ObjectId, ref: 'User' },
  isDeleted: { type: Boolean, default: false },
  deletedAt: { type: Date, default: null }
});

// Index for performance (filter out deleted in all queries)
postSchema.index({ isDeleted: 1 });

// Soft delete method
postSchema.methods.softDelete = async function() {
  this.isDeleted = true;
  this.deletedAt = new Date();
  return this.save();
};

// Query helper — always exclude soft-deleted docs
postSchema.pre(/^find/, function() {
  this.where({ isDeleted: false }); // automatically applied to all find queries
});

// Restore soft-deleted document
postSchema.methods.restore = async function() {
  this.isDeleted = false;
  this.deletedAt = null;
  return this.save();
};

// Controller
const deletePost = asyncHandler(async (req, res) => {
  const post = await Post.findById(req.params.id);
  if (!post) return res.status(404).json({ message: 'Post not found' });
  await post.softDelete();
  res.json({ message: 'Post deleted successfully' });
});

// Admin: get all including deleted
const getAllPosts = asyncHandler(async (req, res) => {
  const posts = await Post.find({}).setOptions({ bypassGlobalFilter: true });
  res.json(posts);
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 100. What are the latest trends in MERN stack development (2024–2025)?

| Trend | Description |
| ----- | ----------- |
| **Next.js App Router** | React Server Components + Server Actions replacing Express for many use cases |
| **TypeScript everywhere** | TypeScript now standard in both frontend (React) and backend (Node/Express) |
| **Bun runtime** | Drop-in Node.js replacement — 3-4x faster (gaining adoption in 2024-25) |
| **Drizzle ORM / Prisma** | Type-safe ORMs gaining popularity alongside/over Mongoose |
| **tRPC** | End-to-end type-safe API layer — shares types between Express + React without REST/GraphQL |
| **Turborepo / Nx** | Monorepo tooling becoming standard for full-stack MERN projects |
| **Hono.js** | Lightweight Express alternative — faster, edge-compatible |
| **Socket.IO → native WebSockets** | Modern browsers support WebSocket API natively; Socket.IO less needed |
| **AI integration** | OpenAI, Anthropic, Vercel AI SDK integrated into MERN apps |
| **Containerization** | Docker + Docker Compose standard for local development |
| **MongoDB Atlas Vector Search** | AI/ML-powered semantic search built into MongoDB |
| **React 19 + Server Actions** | Replacing Express API routes for mutation operations in Next.js |

```javascript
// tRPC example — end-to-end type safety
// server
const appRouter = router({
  getUser: publicProcedure
    .input(z.object({ id: z.string() }))
    .query(async ({ input }) => {
      return User.findById(input.id);
    })
});
// client — full TypeScript autocomplete, no manual API types!
const user = await trpc.getUser.query({ id: '123' }); // type-safe!
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

<div align="center">

## 🎉 You've covered all 100 MERN Stack Interview Questions!

---

**If this repo helped you prepare, please give it a ⭐**

[![Star this repo](https://img.shields.io/github/stars/sisi-tarak/mern-interview-questions?style=social)](https://github.com/sisi-tarak/mern-interview-questions)

---

### 📲 Follow Sisi for more tech interview prep content

[![Instagram](https://img.shields.io/badge/Instagram-%40sisi__tarakk-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sisi_tarakk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sisindri%20Singamsetti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisitarak)
[![GitHub](https://img.shields.io/badge/GitHub-sisi--tarak-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sisi-tarak)

---

### 🤝 Want to contribute?

Found a mistake, have a better explanation, or want to add more questions?

**[Open a Pull Request](https://github.com/sisi-tarak/mern-interview-questions/pulls)** — all contributions are welcome! 🙌

---

### 📦 More Interview Repos

| Status | Repository |
| ------ | ---------- |
| ✅ Live | [react-interview-questions](https://github.com/sisi-tarak/react-interview-questions) |
| ✅ Live | [nodejs-interview-questions](https://github.com/sisi-tarak/nodejs-interview-questions) |
| ✅ Live | [mern-interview-questions](https://github.com/sisi-tarak/mern-interview-questions) |
| 🔜 Coming | dsa-interview-questions |
| 🔜 Coming | java-interview-questions |
| 🔜 Coming | python-interview-questions |

⭐ **Star this repo to get notified when new repos drop!**

---

## Disclaimer

The questions in this repository are compiled from frequently asked interview questions across MNC companies including TCS, Infosys, Wipro, Cognizant, HCL, Capgemini, Accenture, Amazon, Flipkart, and other product companies. We cannot guarantee these exact questions will appear in your interview. The goal is to build conceptual clarity and real-world understanding, not memorization.

Good luck with your interview! 😊

*Made with ❤️ by [Sisi](https://instagram.com/sisi_tarakk) | Helping Telugu tech students crack their dream jobs 🚀*

</div>
