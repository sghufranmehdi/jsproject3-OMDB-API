**Assignment: Movie Search Web Application**

**Objective:** Create a web application that allows users to search for movies using the OMDB API, filter the results by the year of release, handle errors, and persist data using localStorage.

**Instructions:**

1. Sign up for a free API key from [OMDb API](http://www.omdbapi.com/).

2. Create an HTML page with the following elements:

   - Two input fields: one for the movie name and one for the year of release.
   - A button to submit the search query.

3. Implement a function to handle the click event of the button:

   - Make an API call to OMDB using the provided API key, searching for movies based on the user's input.
   - Retrieve the search results.

4. Initially, display a single movie in an HTML element (e.g., a div) and insert it into an unordered list (ul) as a list item (li).

5. Use the JavaScript `map` function to map the entire array of search results into HTML elements (e.g., divs or li elements) and insert them into the ul as list items.

6. Implement a year launched filter:

   - If a value is present in the year launched field, read that value.
   - Filter the movies array to include only those launched in or after the specified year.
   - Show the updated list of movies with the year launched filter applied.

7. Handle the case when no movie is found for the entered name:

   - Generate a popup in the center of the screen with an error message.
   - Include a button in the popup to close it.

8. Implement data persistence:
   - Store the movie data in the browser's localStorage when the page is being unloaded (use the `beforeunload` event).
   - Retrieve the stored data from localStorage when the page is loaded.
   - If no data is present in localStorage, display a blank list.

**Submission:**

1. Create a detailed HTML file that includes the webpage structure.

2. Create a JavaScript file containing the code for the described functionality.

3. Provide CSS styling to make the page visually appealing.

4. Write a report explaining the logic and structure of your code (Optional)

5. Demonstrate the functioning of your web application with screenshots.

**Note:** Ensure that the movie data is not lost when the page is refreshed by implementing localStorage.
