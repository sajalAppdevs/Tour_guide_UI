# Travel App UI In Flutter

A beautiful and modern travel app UI template built with Flutter, showcasing various tourist destinations with an intuitive and responsive interface. This project demonstrates the implementation of a multi-screen travel guide application with smooth navigation and attractive visuals.

## Features

- Clean and modern UI design
- Three well-designed screens:
  - Starting Screen: App introduction and welcome screen
  - Home Screen: Display of various cities with attractive cards
  - View Screen: Detailed information about selected cities
- Smooth navigation between screens
- Responsive layout that works on both Android & iOS
- Custom curved navigation bar
- Beautiful image assets of various tourist destinations

## Screenshots
![mobile](https://user-images.githubusercontent.com/97346744/198978464-0022cbd6-b640-4c3a-9780-6e936ba1111d.PNG)

## Dependencies

- Flutter SDK (>=2.18.2 <3.0.0)
- get: ^4.6.5 - For state management
- curved_navigation_bar: ^1.0.3 - For custom bottom navigation
- cupertino_icons: ^1.0.2 - For iOS style icons

## Getting Started

### Prerequisites

- Flutter SDK installed on your machine
- Android Studio / VS Code with Flutter extensions
- Basic knowledge of Flutter development

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Navigate to the project directory:
```bash
cd Tour_guide_UI
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## Project Structure

```
lib/
├── const.dart          # Constants and theme configurations
├── main.dart           # Application entry point
└── view/
    ├── Home_Screen.dart    # Main screen with city listings
    ├── Main_Screen.dart    # Starting screen of the app
    └── Visit_Screen.dart   # Detailed city view screen
```

## Assets

The project includes various high-quality images of tourist destinations located in the `images/` directory:
- applogo.png - Application logo
- Various city images (islamabad.jpg, karachi.jpg, lahore.jpg, etc.)

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to all contributors who helped in building this UI template
- Image credits to their respective owners

