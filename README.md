# SkyScanner Web Application

SkyScanner is a web-based climate utility designed to provide users with actual-time weather statistics, forecasts, and information updates. The utility offers a user-friendly interface for searching climate info by using location, which uses both guide input and the person's modern place. moreover, the utility capabilities of a blog and climate news phase to keep users informed approximately the trendy weather-associated traits.

### files and Folders

- **index.html**: the primary page of the utility where customers can search for weather data.
- **news.html**: A dedicated web page for displaying the today's climate information, along with motion pictures and articles.
- **blog.html**: The weather weblog page in which customers can study articles and guidelines associated with climate and climate.
- **style.css**: the principle stylesheet that offers styling throughout all pages in the utility.
- **script.js**: incorporates all the JavaScript functionality for managing climate facts, user interactions, and API requests.
- **news.js**: consists of the JavaScript capability specific to the weather news web page, including carousel manipulate for information films.

### Key features

1. **climate search**:
   - customers can look for climate facts by means of getting into a region manually.
   - The app also supports the use of the user's contemporary area to fetch climate statistics.
   - climate facts includes present day conditions, a five-day forecast, and applicable precautions.

2. **climate information**:
   - The `news.html` web page presentations the brand new climate information updates.
   - includes a video carousel presenting weather-associated movies.
   - information articles provide records on current weather events, advisories, and warnings.

3. **weather blog**:
   - The `blog.html` page hosts diverse weblog posts and tips associated with climate.
   - customers can read approximately topics like weather safety, weather trade, and seasonal suggestions.

### how to Use

1. **climate search**:
   - Navigate to the home page (`index.html`).
   - enter a place inside the search bar or use the location button to get climate data in your present day location.
   - View the contemporary climate, 5-day forecast, and precautions based on weather conditions.

2. **climate news**:
   - Navigate to the news page (`information.html`) by means of clicking on the "weather news" button from the home page.
   - Browse via the modern-day news articles and watch videos in the carousel.

3. **weather weblog**:
   - Navigate to the blog page (`blog.html`) to study articles associated with weather and climate.
   - The blog covers various topics, from safety tips to environmental discussions.

### Setup and installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/skyscanner-climate-app.git
   ```

2. **Open the mission**:
   - Navigate to the task directory.
   - Open `index.html` in a web browser to begin the application.

3. **Dependencies**:
   - The software uses Tailwind CSS for application-first styling.
   - It additionally integrates with the OpenWeatherMap API for fetching weather statistics.
   - ensure you've got an API key from OpenWeatherMap to replace the placeholder in `script.js`.

### API Integration

- **OpenWeatherMap API**: 
  - The application fetches climate facts using the OpenWeatherMap API. 
  - update the `API_KEY` in `script.js` with your real API key to make certain the app features efficiently.
