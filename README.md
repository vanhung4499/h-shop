# H-Shop

## Getting Started

Welcome to H-Shop! This is a simple e-commerce website that I built to practice my full-stack development skills. The website is built with NextJS, MongoDB, and Redux.

**Project Live Demo**

- Docker Deployment: Upcoming
- Vercel Deployment: Upcoming

If you like the project, please give it a star. It will help me to keep going and improve the project. Thank you!

## Background

### Why I built this project

As a backend developer, my frontend skills are not as good as my backend skills. After a interview for full-stack position, I realized that I need to improve my frontend skills. So I decided to build a e-commerce website to practice my frontend skills.

### Objective

- Built a complete, well-structured, and scalable e-commerce website.
- Improved my frontend skills, especially in React, Redux, and NextJS.
- Use a series cutting-edge technologies: NextJS, TailwindCSS, Headless UI, Redux-Toolkit-RTK query, JWT, Docker, and MongoDB, etc.
- Focus on frontend (user interface and user experience), backend is simple enough to support the frontend.

## Technologies

Technologies that I used in this project:

- TypeScript: main language.
- NextJS: main framework.
- TailwindCSS: for CSS styling.
- Headless UI: for UI components.
- Redux Toolkit: for state management.
- RTK Query: A powerful data fetching and caching tool.
- JWT: for aauthentication.
- MongoDB: for database.
- Docker: for deployment.

## Demo

Upcoming

## Project Structure

🏗️ **H-Shop Project Structure:**

**Key structure explanation:**

- 📁 **app**: Main code of the application

  - 📁 **main**: Main application components
    - 📁 **client-layout**: Common layout pages for the user side
    - 📁 **empty-layout**: Common blank layout pages
    - 📁 **admin**: Admin pages
    - 📄 **layout.ts**: Main layout configuration
    - 📁 **profile**: User profile page
  - 📄 **StoreProvider.js**: Global state management provider
  - 📁 **api**: API request-related routes
    - 📁 **auth**: User authentication API
    - 📁 **banner**: Advertisement banner API
    - 📁 **category**: Product category API
    - ...

- 📁 **components**: Reusable React components
- 📁 **helpers**: Helper functions and tools

  - 📁 **api**: API request-related helper functions
  - 📄 **auth.ts**: Helper functions related to user authentication
  - ...

- 📁 **hooks**: Custom React hooks
- 📁 **models**: Data model definitions
- 📁 **public**: Static resources, such as images, fonts, etc.
- 📁 **store**: Configuration related to Redux state management
  - 📁 **services**: RTK Query
  - 📁 **slices**: Redux Toolkit
- 📁 **styles**: Style files
- 📁 **utils**: General utilities
- ...

This structure is designed to make project easy to navigate and maintain. It is also scalable and easy to expand.

## Installation and Usage

### Local Development

1. Clone the project

````bash
```bash
    git clone https://github.com/vanhung4499/h-shop.git
````

2. Installl dependencies

```bash
    npm install
    # OR
    yarn install
```

3. Modify the environment variables

```bash
    cp .env.example .env.local
```

4. Start MongoDB server

You can run mongodb server locally or use docker for create an instance. I have already included a docker-compose file for this purpose.

```bash
    docker-compose up -d mongodb
```

### Docker

I have already included a docker-compose file for this purpose. You can start the project with the following command:

```bash
    docker-compose up -d
```

# Deployment

This project is hosted on Vercel. You can deploy the project on Vercel by following these steps:

Upcoming...

## License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2024 Hung Nguyen
