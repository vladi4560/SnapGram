# SnapGram



A web application similar to Instagram, built with React, Next.js, TypeScript, Vite, Tailwind CSS, and utilizing Appwrite for database, authentication, and storage. It integrates TanStack, Shadcn, and react-dropzone.

## Table of Contents

- [About](#about)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)

## About

This project is a web application resembling Instagram, developed using React, Next.js, TypeScript, Vite, and Tailwind CSS. It utilizes [Appwrite](https://appwrite.io/) for its database, authentication, and storage functionalities. The application integrates TanStack, Shadcn, and react-dropzone libraries for various functionalities and features.

### Technologies Used

- ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
- ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
- ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
- ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
- Appwrite
- TanStack
- Shadcn
- react-dropzone

## Features

List of features or functionalities your application provides:

- Upload posts
- Edit posts
- View other users' posts
- Like posts
- Search for posts
- Explore posts
- User profiles
- Follow other profiles

## Installation

Follow these steps to set up and run the project locally:

```
bash
$ git clone https://github.com/yourusername/your-repository.git
$ cd your-repository
$ npm install
# Configure Appwrite: Obtain your Appwrite credentials and set them up according to the documentation.
$ npm run dev
```
## Project structure
```
$PROJECT_ROOT
├── index.html             # Entry point
├── public
│   └── assets
│       ├── icons
│       └── images
└── src
    ├── _auth
    │   └── forms
    ├── components
    │   ├── forms
    │   ├── shared      # Global components
    │   └── ui          # Shadcn
    ├── constants       # Constant variables
    ├── context
    ├── hooks
    ├── lib
    │   ├── appwrite    # Appwrite config
    │   ├── react-query # React-query config
    │   └── validation  # Schema validation with zod
    ├── _root
    │   └── pages
    └── types           # Custom types
```
