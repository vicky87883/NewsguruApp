# NewsGuru - React Native News App

![NewsGuru Logo](assets/logo.png)

NewsGuru is a React Native mobile application designed to provide users with the latest news articles. The app fetches data from the NewsGuru API and displays articles in a user-friendly, professional UI. Users can explore news articles, view details, and read further content on an external site.

## Features

- **News Feed**: Browse the latest news articles with headlines, images, and tags.
- **Article Details**: View in-depth details of each article.
- **Professional UI**: Enhanced design with icons, tag colors, and improved layout.
- **External Links**: Open articles on external sites for a complete reading experience.

## Screenshots

> Include screenshots of the app's home screen, article details screen, and navigation if possible.

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/vicky87883/NewsGuru.git
    cd NewsGuru
    ```

2. **Install Dependencies**:

    ```bash
    npm install
    ```

3. **Start the App**:

    For iOS:
    ```bash
    npx expo start --ios
    ```

    For Android:
    ```bash
    npx expo start --android
    ```

## Configuration

Ensure the API URL in `HomeScreen.tsx` is set to the NewsGuru API:

```javascript
axios.get('https://demo.api')
Project Structure
plaintext
Copy code
├── app
│   ├── _layout.tsx
│   ├── +html.tsx
│   ├── +not-found.tsx
├── assets
│   └── logo.png
├── components
│   └── NewsCard.tsx
├── constants
├── hooks
├── node_modules
├── scripts
├── screens
│   ├── HomeScreen.tsx
│   └── NewsDetailScreen.tsx
└── App.js
Building the App
Expo has deprecated expo build, so use EAS CLI to build the app:

Install EAS CLI:

bash
Copy code
npm install -g eas-cli
Login to Expo:

bash
Copy code
eas login
Configure Build:

bash
Copy code
eas build:configure
Build for Android:

bash
Copy code
eas build -p android
Build for iOS (requires Apple Developer account):

bash
Copy code
eas build -p ios
Contributing
We welcome contributions to NewsGuru! Please fork this repository and submit pull requests for any new features, improvements, or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for more information.

