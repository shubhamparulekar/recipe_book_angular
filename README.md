# 🍳 Recipe Book (Angular)

A modern, responsive recipe book application built with Angular. Users can manage recipes—create, read, update, and delete (CRUD)—and enjoy an immersive, menu-driven interface.

---

## 🚀 Features

- 🌟 **Add New Recipes**: Easy-to-use form with fields for title, description, ingredients, and instructions  
- ✏️ **Edit Recipes**: Modify any detail of existing recipes  
- 🗑️ **Delete Recipes**: Remove recipes with confirmation prompts  
- 📋 **Recipe Listing**: Browse all recipes in a clean, list-based UI  
- 🔍 **Search & Filter**: Quickly find recipes by title or ingredient  
- 🔄 **Routing**: Navigate between pages (list, detail, add/edit, 404)  
- 📱 **Responsive Design**: Adapts beautifully to desktop and mobile screens  

---

## 🧰 Tech Stack

- **Framework**: Angular (v14+)
- **UI**: Angular Material or Bootstrap (if used)
- **State**: Angular’s reactive forms, services, and RxJS
- **Storage**: LocalStorage (for persistence) or optional backend API
- **Language**: TypeScript, SCSS/CSS, HTML  

---

## 📦 Demo & Screenshots (optional)

![Home](images/home.png)  
![Add Recipe](images/add-recipe.png)

*(Add screenshots or animated GIFs here)*

---

## 📁 Project Structure

recipe_book_angular/
├── src/
│ ├── app/
│ │ ├── components/
│ │ │ ├── recipe-list/ # Lists all recipes
│ │ │ ├── recipe-detail/ # Displays details
│ │ │ └── recipe-form/ # Add/Edit form
│ │ ├── models/
│ │ │ └── recipe.model.ts # Recipe interface definition
│ │ ├── services/
│ │ │ └── recipe.service.ts # CRUD & storage logic
│ │ ├── app-routing.module.ts # Application routes
│ │ └── app.module.ts # Root module
│ ├── assets/
│ │ └── icons, images…
│ └── styles.scss # Global styles
│
├── angular.json
├── package.json
└── README.md


---

## 🛠️ Setup & Running Locally

### Prerequisites:

- Node.js v14+  
- npm or Yarn  

### Steps:

1. Clone the repo:
   ```bash
   git clone https://github.com/shubhamparulekar/recipe_book_angular.git
   cd recipe_book_angular

    Install dependencies:

npm install
# or yarn install

Run the development server:

    npm start
    # or ng serve

    Open your browser to http://localhost:4200.

## ⚙️ Configuration & Customization

    Storage:

        Uses localStorage by default

        To switch to a backend API, update recipe.service.ts, and adjust models and endpoints

    Styling:

        Modify global styles in styles.scss

        Add themes, fonts, and icons as needed

    Dependencies:

        Use Angular CLI to add Angular Material (ng add @angular/material) or Bootstrap

        Adjust components to use your preferred UI framework

## ✅ Available Scripts
Command	Description
npm start	Launch development server on port 4200
npm run build	Build production-ready files (dist/)
npm test	Conduct unit tests with Karma/Jasmine
npm run lint	Run linter to check for code issues

## 🧑‍💻 Contributing

Contributions are very welcome! To add features or fix bugs:

    Fork the repo

    Create a feature branch: git checkout -b feature/my-feature

    Make your changes, commit them, and push: git push origin feature/my-feature

    Open a Pull Request detailing your improvements

##📝 Code Style & Thoughts

    Uses Angular best practices: modules, components, services

    Form-handling performed through Reactive Forms

    Navigation logic handled by Angular Router

    State management is minimal—easily extendable for NgRx

    Clean, modular, and test-ready code structure

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.
✨ Acknowledgements

Built using insights and patterns from the Angular community and official documentation.
