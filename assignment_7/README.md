# Assignment 7: Route and Query Parameters

An Express.js application demonstrating route parameters and query parameters.

## Setup

Install the dependencies:

```bash
npm install
```

Start the server:

```bash
npm start
```

The server runs at `http://localhost:3000`.

## Assignment 1: Route Parameters

Route: `GET /student/:id`

Example:

```text
http://localhost:3000/student/101
```

Output:

```text
Student ID: 101
```

## Assignment 2: Query Parameters

Route: `GET /search`

Example:

```text
http://localhost:3000/search?name=Shubh&course=Node.js
```

Output:

```text
Name: Shubh
Course: Node.js
```

When no query parameters are provided:

```text
http://localhost:3000/search
```

Output:

```text
No search data provided.
```

## Assignment 3: Student Profile

Route: `GET /student/:id` with `name` and `course` query parameters.

Example:

```text
http://localhost:3000/student/101?name=Shubh&course=FullStack
```

Output:

```text
Student ID: 101
Name: Shubh
Course: FullStack
```

## Concepts Covered

- Dynamic routes
- Route parameters using `req.params`
- Query parameters using `req.query`
- Express.js routing
