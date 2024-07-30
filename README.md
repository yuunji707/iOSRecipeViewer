# iOS Fetch Exercise

A SwiftUI-based iOS application that allows users to browse dessert recipes, view detailed meal information, save favorites, and discover random meals. This app demonstrates modern iOS development practices, including async/await for network calls, MVVM architecture, and SwiftUI for the user interface.

## Setup Instructions

1. **Clone the repository**
   ```
   git clone https://github.com/yourusername/iOSFetchExercise.git
   cd iOSFetchExercise
   ```

2. **Open the project in Xcode**
   - Double-click on the `iOSFetchExercise.xcodeproj` file, or open it from within Xcode.

3. **Select a simulator or device**
   - In Xcode, select your target device from the scheme menu in the top left corner.

4. **Build and run the project**
   - Press `Cmd + R` or click the "Play" button in Xcode to build and run the app.

## Features

- **Dessert List**: Browse a list of dessert recipes fetched from TheMealDB API.
- **Meal Details**: View detailed information about each meal, including ingredients, instructions, and links to external resources.
- **Favorites**: Save and manage your favorite meals for quick access.
- **Random Meal**: Discover new recipes with a random meal generator.
- **Search**: Easily find desserts using the search functionality.

## Project Structure

- `iOSFetchExerciseApp.swift`: The main entry point of the application.
- `ContentView.swift`: The root view of the application, managing the tab-based navigation.
- `APIService.swift`: Handles all API calls to TheMealDB.
- `MealsViewModel.swift`: Manages the state for the list of dessert meals.
- `MealDetailViewModel.swift`: Manages the state for individual meal details.
- `FavoriteMealsViewModel.swift`: Handles the logic for saving and retrieving favorite meals.
- `RandomMealViewModel.swift`: Manages the state for the random meal feature.
- View files (`MealView.swift`, `MealDetailView.swift`, etc.): Contain the SwiftUI views for different screens in the app.

## API

This app uses [TheMealDB API](https://www.themealdb.com/api.php) to fetch meal data. No API key is required for the free tier, which this app uses.

## Testing

Unit tests are included to ensure the reliability of core functionalities. To run the tests:

1. In Xcode, select the test target from the scheme menu.
2. Press `Cmd + U` or go to Product > Test to run all tests.

