# WorldWise

WorldWise is a React-based application designed to display city and country data on an interactive map. The application allows users to browse, search, and view information about different cities and countries around the world.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Available Scripts](#available-scripts)
- [Dependencies](#dependencies)
- [License](#license)
- [Contributing](#contributing)

## Installation

To get started with the WorldWise application, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/yonathandevpro/worldwise.git
cd worldwise
npm install
```

## Usage

After installation, you can start the development server to view the application in your browser.

```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

## Project Structure

```plaintext
worldwise/
│
├── public/                        # Public assets
│   ├── bg.jpg                     # Background image
│   ├── icon.png                   # Application icon
│   ├── img-1.jpg                  # Additional image 1
│   ├── img-2.jpg                  # Additional image 2
│   ├── logo.png                   # Application logo
│   └── vite.svg                   # Vite logo
│
├── src/                           # Source files
│   ├── components/                # Reusable components
│   │   ├── AppNav.jsx             # Navigation component
│   │   ├── BackButton.jsx         # Back button component
│   │   ├── Button.jsx             # Generic button component
│   │   ├── City.jsx               # City information component
│   │   ├── CityItem.jsx           # Individual city item component
│   │   ├── CityList.jsx           # List of cities component
│   │   ├── CountryItem.jsx        # Individual country item component
│   │   ├── CountryList.jsx        # List of countries component
│   │   ├── Footer.jsx             # Footer component
│   │   ├── Form.jsx               # Form component
│   │   ├── Logo.jsx               # Logo component
│   │   ├── Map.jsx                # Map component
│   │   ├── Message.jsx            # Message component
│   │   ├── PageNav.jsx            # Page navigation component
│   │   ├── Sidebar.jsx            # Sidebar component
│   │   ├── Spinner.jsx            # Loading spinner component
│   │   ├── SpinnerFullPage.jsx    # Full-page loading spinner component
│   │   └── User.jsx               # User component
│   │
│   ├── contexts/                  # Context providers
│   │   ├── CitiesContext.jsx      # Context for managing city data
│   │   └── FakeAuthContext.jsx    # Context for fake authentication
│   │
│   ├── hooks/                     # Custom hooks
│   │   ├── useGeoLocation.js      # Hook for geolocation
│   │   └── useUrlPosition.js      # Hook for URL position management
│   │
│   ├── pages/                     # Page components
│   │   ├── AppLayout.jsx          # Main application layout
│   │   ├── Homepage.jsx           # Homepage component
│   │   ├── Login.jsx              # Login page component
│   │   ├── PageNotFound.jsx       # 404 error page component
│   │   ├── Pricing.jsx            # Pricing page component
│   │   └── Product.jsx            # Product page component
│   │
│   ├── index.css                  # Global CSS styles
│   ├── main.jsx                   # Application entry point
│   └── App.jsx                    # Root application component
│
├── data/                          # Data files
│   └── cities.json                # City data in JSON format
│
├── .gitignore                     # Git ignore file
├── eslint.config.js               # ESLint configuration
├── index.html                     # HTML template
├── package-lock.json              # Package lock file
├── package.json                   # Package manifest
├── README.md                      # Project documentation
└── vite.config.js                 # Vite configuration
```

## Features

- **Interactive Map**: Explore and interact with cities and countries on a map.
- **City & Country Lists**: Browse detailed information on various cities and countries.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Custom Hooks**: Utilize custom hooks for geolocation and URL position management.
- **Fake Authentication**: Context-based fake authentication for demonstration purposes.
- **Loading Indicators**: Show loading spinners while data is being fetched.

## Available Scripts

In the project directory, you can run:

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the app for production.
- `npm run preview`: Previews the production build locally.
- `npm run lint`: Lints the code for potential issues.

## Dependencies

- **React**: JavaScript library for building user interfaces.
- **Leaflet**: JavaScript library used for creating interactive maps.
- **Vite**: Fast build tool and development server.
- **React Router**: Declarative routing for React applications.

Refer to `package.json` for the full list of dependencies.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.
