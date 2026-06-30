# Express CRUD API

A simple CRUD API built with Node.js and Express. Data is stored in a `data.json` file using the Node.js `fs` module.

## Features

- Get all items
- Create a new item
- Update an item
- Delete an item

## Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/` | Get all items |
| POST | `/` | Create a new item |
| PUT | `/:id` | Update an item |
| DELETE | `/:id` | Delete an item |

## Run the Project

```bash
npm install
npm run dev
```

The server runs with **nodemon** at:

```
http://localhost:3000
```

## Technologies

- Node.js
- Express.js
- Nodemon
- File System (`fs`)