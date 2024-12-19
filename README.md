# Weather App using Node.js

A simple web application that provides real-time weather updates for any city around the world. This project is built using **Node.js** and integrates with a weather API to fetch accurate weather data.

## Features

- Search for the current weather of any city.
- Displays temperature in Celsius.
- Provides weather conditions (e.g., cloudy, sunny).
- Includes the city's name and country.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **API Integration:** OpenWeatherMap (or your preferred weather API)

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/the-abhishekroy/Weather_App.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Weather_App
   ```

3. Install the required dependencies:
   ```bash
   npm install
   ```

4. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/) (or your chosen weather API).

5. Create a `.env` file in the root directory and add your API key:
   ```env
   API_KEY=your_api_key_here
   ```

6. Start the server:
   ```bash
   npm start
   ```

7. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## File Structure

```
Weather_App/
├── public/
│   ├── style.css        # Styling for the app
├── views/
│   ├── index.ejs        # EJS template for the frontend
├── app.js               # Main application file
├── package.json         # Project metadata and dependencies
├── .env                 # Environment variables
```

## Usage

1. Enter the name of the city in the search bar.
2. Click on "Get Weather" to fetch the weather details.
3. View the temperature, weather condition, and location.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Abhishek Roy**  
[GitHub Profile](https://github.com/the-abhishekroy)

---

Feel free to contribute, report bugs, or request new features! Happy coding!
