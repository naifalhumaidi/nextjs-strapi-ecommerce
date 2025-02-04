# Next.js & Strapi E-Commerce Application

This is an e-commerce application built using Next.js v15, React v19, TypeScript, Chakra UI, Strapi, TanStack Query (formerly React Query), ESLint, and aliases for a smooth development experience.. The application provides a seamless shopping experience with a modern user interface and a robust backend for managing products and orders.

## Features

- **Next.js v15**: The latest version of the React framework for production.
- **React v19**: The latest version of React for building user interfaces.
- **Strapi**: A headless CMS that provides a flexible API for managing content.
- **Chakra UI**: A simple, modular, and accessible component library.
- **TanStack Query**: A powerful data-fetching library for managing server state.
- **TypeScript**: Strongly typed programming language that builds on JavaScript.
- **ESLint**: A tool for identifying and fixing problems in JavaScript code.
- **Aliases**: Simplified import paths for better code organization.

## Getting Started

To set up the nextjs-strapi-ecommerce, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/naifalhumaidi/nextjs-strapi-ecommerce.git
   
2. **Navigate into the project directory:**
   ```bash
   cd nextjs-strapi-ecommerce

3. **Set up the frontend:**

   To set up the Nextjs frontend:

   - **Navigate to the frontend directory::**
      ```bash
      cd frontend
   
   - **Install dependencies using pnpm:**
      ```bash
      pnpm install

   - **Start the development server:**
      ```bash
      pnpm run dev

   - **Open your browser and go to http://localhost:3000.**

4. **Set up the backend:**

   To set up the Strapi backend:

   - **Navigate to the backend directory:**

      ```bash
      cd backend

   - **Install Strapi dependencies:**

      ```bash
      pnpm install

   - **Run the Strapi server:**

      ```bash
      pnpm run develop

   - **Access the Strapi admin panel at http://localhost:1337/admin to create and manage your content types.**
 
## Customization

Feel free to modify the project structure, add new features, and customize the code as per your requirements. This application is designed to be flexible and easy to adapt.

## Chakra UI Customization

To customize your Chakra UI theme, edit the theme.js file and add your custom styles in the styles/globals.css file.

## TanStack Query Configuration

You can customize your TanStack Query settings in the queryClient.js file to fit your data-fetching needs.

## ESLint Configuration

You can modify the ESLint rules in the .eslintrc.js file to fit your coding style preferences.

## License

This project is licensed under the MIT License - see the LICENSE file for details.