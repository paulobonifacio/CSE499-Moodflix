# 🎬 MoodFlix

“Your mood deserves the perfect movie.”

MoodFlix is a web application that recommends movies based on your mood.  
It uses **sentiment analysis** and **movie data APIs** to create a personalized and emotional movie discovery experience.

---

## 🌟 Purpose

Most streaming services offer endless lists of movies but fail to match what users *feel like watching*.  
MoodFlix bridges that gap by understanding the user’s mood and suggesting films that align with it — whether you’re happy, sad, excited, or nostalgic.

---

## 🚀 Features

- 🧠 **Mood Detection:** Uses the Hugging Face API to analyze user input and detect mood.  
- 🎥 **Movie Recommendations:** Fetches movie data (title, genre, rating, poster) from TMDb API based on detected mood.  
- 💾 **Favorites:** Allows users to save favorite movies locally using `localStorage`.  
- 💬 **Dynamic Search:** Users can manually explore movies by genre or keyword.  
- ⚡ **Lazy Loading:** Optimizes performance by loading images only when needed.  
- 📱 **Responsive Design:** Works perfectly on both desktop and mobile devices.  
- 🧹 **Clean Code:** Linting with ESLint ensures consistent and readable JavaScript.  
- 💫 **Smooth Animations:** Subtle transitions and effects for a pleasant user experience.

---

## 🛠️ Technologies Used

- **HTML5** – structure and semantic layout  
- **CSS3** – styling and responsive design (Flexbox & Grid)  
- **JavaScript (ES6+)** – interactivity and API integration  
- **TMDb API** – for movie data and posters  
- **Hugging Face API** – for sentiment/mood analysis  
- **localStorage** – to save user preferences  
- **ESLint** – code formatting and quality assurance  
- **GitHub Pages** – hosting and deployment  

---

## 💡 How It Works

1. The user enters a word or phrase describing their mood.  
2. The app sends the text to the Hugging Face API to analyze sentiment.  
3. Based on the detected mood, MoodFlix fetches a list of related movies from TMDb.  
4. The user can view, save, or explore recommended movies.  

