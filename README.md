
# 🍳 Cooking Up! - Meal Categories and Recipe App

Cooking Up! is a Flutter-based mobile application designed to help users explore and manage meal categories and recipes. With a clean and intuitive interface, users can browse various meal categories, apply dietary filters, and save their favorite recipes for quick access. This project demonstrates the power of Flutter and modern app design principles.

---

## 🚀 Features

- **Category Browser**:  
  Explore different meal categories like **Italian**, **Turkish**, **Breakfast**, and more in a visually appealing grid layout.

- **Favorites**:  
  Save your favorite meals for easy access in a dedicated favorites section.

- **Filters**:  
  Apply dietary filters to find meals that match your preferences:
  - Gluten-free
  - Lactose-free
  - Vegetarian
  - Vegan

- **Dark Mode Support**:  
  Enjoy a modern, dark-themed user interface for better readability.

- **Responsive Navigation**:
  - Hamburger menu for quick access to Meals and Filters.
  - Bottom navigation bar for seamless switching between Categories and Favorites.

---

## 🛠️ Technologies Used

- **Flutter**: Cross-platform UI toolkit for building beautiful and fast mobile apps.
- **Dart**: Programming language used for Flutter app development.
- **Material Design 3**: Enhanced UI elements with modern styling and color theming.
- **Google Fonts (Lato)**: Clean and professional typography for better text readability.

---

## 📂 Project Structure


## **lib/**

```
lib/
├── models/               # Folder containing data models.
│   ├── category.dart     # Category model: Defines properties like id and title for categories.
│   ├── meal.dart         # Meal model: Includes properties of meals (name, duration, ingredients).
│   └── filters.dart      # Filter model: Defines filters selected by the user.
│
├── screens/              # Folder containing the app's screens.
│   ├── categories_screen.dart  # Main screen listing all categories.
│   ├── favorites_screen.dart   # Screen showing favorite meals.
│   ├── filters_screen.dart     # Screen where users can apply filters.
│   └── meal_detail_screen.dart # Screen displaying details of a selected meal.
│
├── widgets/              # Folder for reusable custom widgets.
│   ├── category_item.dart       # Widget designing the category tiles.
│   ├── meal_item.dart           # Widget listing meals.
│   └── main_drawer.dart         # Navigation menu for the app.
│
├── utils/                # Utility functions or general settings.
│   └── app_colors.dart         # Defines the app's color palette.
│
└── main.dart             # Entry point of the application.
```

---

### **Detailed Explanations**

#### **1. models/**
- **category.dart**: Contains properties like id and title for categories.
- **meal.dart**: Includes meal properties (name, description, duration, difficulty, etc.).
- **filters.dart**: Stores filter settings defined by the user (e.g., dietary preferences).

#### **2. screens/**
- **categories_screen.dart**: Displays all categories in a grid view format.
- **favorites_screen.dart**: Displays the user's favorite meals.
- **filters_screen.dart**: Allows users to filter meals based on dietary preferences.
- **meal_detail_screen.dart**: Shows details of a selected meal (ingredients, steps, etc.).

#### **3. widgets/**
- **category_item.dart**: Creates category tiles. Clicking on a tile navigates to the relevant meal screen.
- **meal_item.dart**: Lists meals and navigates to the detail screen when clicked.
- **main_drawer.dart**: Side menu (drawer) component for navigating between screens.

#### **4. utils/**
- **app_colors.dart**: Defines the color palette used throughout the app (e.g., `primaryColor`, `accentColor`).
---

## 🖥️ Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/cooking-up.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd cooking-up
   ```

3. **Install dependencies**:
   ```bash
   flutter pub get
   ```

4. **Run the app**:
   ```bash
   flutter run
   ```

---

## 🤝 Contributions

Contributions are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add YourFeatureName"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Open a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as needed.

---

### ✨ Screenshots

| Categories Screen                     | Filters Screen                     | Favorites Screen                 |
|---------------------------------------|-------------------------------------|-----------------------------------|
| ![Categories](path/to/categories.png) | ![Filters](path/to/filters.png)    | ![Favorites](path/to/favorites.png) |

---

