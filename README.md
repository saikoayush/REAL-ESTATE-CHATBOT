# Agent Mira Real Estate Chatbot
A full-stack real estate chatbot that helps users find homes based on their preferences. The chatbot fetches and merges data from multiple JSON sources, filters properties based on user input, and displays relevant results interactively.

## 🚀 Features

### ✅ Core Features
- **User Input Handling** – Users enter location, budget, and preferences.
- **Data Merging** – Combines data from three separate JSON files.
- **Filtering** – Returns properties that match user preferences.
- **Chatbot UI** – Interactive chatbot interface built with React.js.
- **MongoDB Integration** – Saves user’s preferred properties.
- **Deployment** – Hosted on GitHub Pages / Vercel / Other cloud platforms.

### ✨ Bonus Features (Optional)
- **Basic NLP** – Uses OpenAI API to improve chatbot responses.
- **Property Comparison** – Allows users to compare multiple properties.
- **Real-Time Search** – Filters properties dynamically as users type.

## 🏗 Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Deployment:** GitHub Pages / Vercel / Other cloud platforms

## 📁 Data Structure

The chatbot uses three JSON files to simulate real-world data sources:
1. **Property Basics (`property_basics.json`)** - Contains ID, title, price, and location.
2. **Property Characteristics (`property_characteristics.json`)** - Includes bedrooms, bathrooms, size, and amenities.
3. **Property Images (`property_images.json`)** - Stores image URLs for each property.

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```bash
  git clone https://github.com/your-username/real-estate-chatbot.git
  cd real-estate-chatbot
```

### 2️⃣ Install Dependencies
```bash
  npm install
```

### 3️⃣ Run the Backend Server
```bash
  cd server
  node index.js
```

### 4️⃣ Run the Frontend
```bash
  cd client
  npm start
```

## 🚀 Deployment
To deploy the chatbot on Vercel or GitHub Pages:
1. **Frontend Deployment:**
   - Run `npm run build` in the client directory.
   - Deploy the `build/` folder on GitHub Pages / Vercel.
2. **Backend Deployment:**
   - Deploy using a cloud service like **Render**, **Heroku**, or **Vercel**.
   - Ensure MongoDB is hosted on **MongoDB Atlas**.

## 💡 Future Enhancements
- Advanced AI-powered chatbot responses
- More property details and analytics
- User authentication and profile management

---
Developed with ❤️ for the Agent Mira Hackathon 🏡💬


