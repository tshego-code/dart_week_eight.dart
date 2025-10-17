Send Money Flutter App – DART-WEEK-8
Overview

This Flutter application demonstrates UI refinement, interactive widgets, custom components, animations, and code quality practices. It is designed as a simple "Send Money" app suitable for a banking or financial application.

The app has been refined to ensure professional spacing, alignment, consistent styling, and usability, while also integrating interactive features and animations.

Features
1. UI Refinement

Clean and consistent spacing and alignment across all screens.

Professional styling applied to text, buttons, cards, and input fields.

Layout designed for user-friendly navigation and readability.

2. Interactive Features

TextFields for entering recipient name and amount.

DropdownButton for selecting a payment method.

Switch to mark transactions as favorite.

Form validation ensures valid recipient name, positive amount, and selected payment method.

3. Custom Widgets

SendMoneyButton – reusable button component.

Custom cards or UI elements can be added for consistent styling across screens.

Supports maintainability and code reusability.

4. Animations & Transitions

Animated success messages using AnimatedOpacity.

Smooth page transitions from login to send money page with PageRouteBuilder.

Enhances user experience and app polish.

5. Code Quality

Clean, modular, and maintainable code.

Proper use of state management within StatefulWidgets.

Refactored code to avoid redundancy and improve readability.

File Structure

main.dart – main application file containing all pages and widgets.

LoginPage – simple login page with navigation to Send Money page.

SendMoneyPage – main page with form, validation, and animations.

SendMoneyButton – reusable custom button widget.

How to Run

Ensure Flutter is installed and your development environment is set up.

Copy the main.dart file into the Flutter project’s lib folder.

Run the app using:

flutter pub get
flutter run


Press Login to navigate to the Send Money page.

Enter recipient details, select payment method, toggle the favorite switch, and press Send Money to see form validation and animated success message.

Author

Tshegofatso Moloto

Email: tshegofatsomoloto72@gmail.com

Location: Kagiso Extension 12, South Africa
