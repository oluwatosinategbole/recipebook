# RecipeBook

RecipeBook is a web-based platform designed to provide a seamless and ad-free culinary experience. Users can search for recipes, upload their own, and interact with the platform by saving favorites. The platform integrates real-time data using the Edamam API, allowing users to access up-to-date recipe information and nutritional data.

## Features
- Advanced Recipe Search: Search for recipes based on keywords, dietary labels, and caloric content.
- User Authentication: Secure login and signup via Firebase, including Google login integration.
- Recipe Uploads: Users can contribute their own recipes, complete with images, ingredients, and instructions.
- Real-Time Data: Access dynamic recipe content from the Edamam API, ensuring up-to-date culinary information.
- Favorites & Likes: Save and like favorite recipes for easy access and personalized recommendations.
- Responsive Design: A sleek, intuitive UI/UX optimized for various devices and screen sizes.

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Flask, SQLite
- Authentication: Firebase
- API Integration: Edamam API

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RecipeBook.git
   cd RecipeBook
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up Firebase and Edamam API keys in a `.env` file:
   ```env
   FIREBASE_API_KEY=your_firebase_api_key
   EDAMAM_APP_ID=your_edamam_app_id
   EDAMAM_APP_KEY=your_edamam_app_key
   ```

5. Run the application:
   ```bash
   flask run
   ```

## Usage
- Register/Login using Firebase or Google Authentication.
- Search for recipes using keywords or dietary labels.
- Upload your own recipes, complete with images and nutritional data.
- Save and like favorite recipes for easy access later.

## Testing
- Run the application locally and test each feature.
- Verify that API requests return expected data and handle exceptions.
- Test user authentication flows, including login, signup, and Google authentication.

## Future Enhancements
- Implement personalized recipe recommendations using user preferences.
- Integrate sentiment analysis to gauge user feedback on recipes.
- Add social sharing capabilities to promote user-generated recipes.


## Authors
- Oluwatosin Ategbole - [GitHub](https://github.com/oluwatosinategbole)
- Ifeoluwa Shode
