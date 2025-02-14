# Conference Expense Planner

## 📌 Overview
The **Conference Expense Planner** is a web application that helps users estimate the total cost of hosting a conference at a convention center. Users can select rooms, add-ons, and meals, and the app dynamically calculates the total expense. A pop-up window displays a detailed breakdown of the selections.

This project is built using **React** with **Redux Toolkit** for state management. It follows best practices for modular UI design, interactivity, and real-time cost calculations.

## 🎯 Features
### **1. Landing Page**
- Displays a background image and company name.
- Includes a paragraph introducing the company and its services.
- A **Get Started** button navigates users to the product selection page.

### **2. Product Selection Page**
Divided into three sections:
- **Room Selection**: Users can choose from five room types and specify the quantity using increment/decrement buttons.
- **Add-ons Selection**: Users can select AV equipment like microphones, speakers, projectors, and signage.
- **Meals Selection**: Users can enter the number of meals required for different options.

Includes:
- A navigation bar with a **Show Details** button that opens a summary pop-up.
- Dynamic cost updates based on user selections.

### **3. Show Details Pop-up**
- Displays a **four-column table** with item name, unit cost, quantity, and subtotal.
- Shows the total cost at the bottom.

## 🚀 Tech Stack
- **Frontend**: React.js
- **State Management**: Redux Toolkit
- **Styling**: CSS
- **Data Handling**: JavaScript ES6, `map()` function for rendering lists

## 📂 Project Structure
```
📦 Conference-Expense-Planner
├── 📂 src
│   ├── 📂 components
│   │   ├── LandingPage.js
│   │   ├── ProductSelection.js
│   │   ├── ShowDetailsPopup.js
│   │   ├── RoomSelection.js
│   │   ├── AddOnsSelection.js
│   │   ├── MealsSelection.js
│   ├── 📂 redux
│   │   ├── store.js
│   │   ├── slices
│   │   │   ├── venueSlice.js
│   │   │   ├── avSlice.js
│   │   │   ├── mealsSlice.js
│   ├── App.js
│   ├── index.js
├── 📜 package.json
├── 📜 README.md
```


## Screenshots
### Landing Page
![![1](https://github.com/user-attachments/assets/bb223b94-d6cf-4107-8dbe-65b1bf009176)

### Room Selection
![2](https://github.com/user-attachments/assets/c1715dd5-ba51-4ef6-9fda-424e73bdec4f)

### Add-ons Selection
![3](https://github.com/user-attachments/assets/7900dc4b-6177-4a77-b386-c5b8b2158efb)

### Meals Selection
![4](https://github.com/user-attachments/assets/40a03f9b-a024-4539-8c98-b9a0474c4aae)

### Show Details Pop-up
![5](https://github.com/user-attachments/assets/1150e960-310d-4695-85d5-415ed024b8b5)


## 🛠️ Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/mohajayyab/ConferenceEventPlannerReact.git
   cd conference-expense-planner
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Run the application:**
   ```sh
   npm start
   ```
## 📌 Usage
1. Click **Get Started** on the landing page.
2. Select rooms, add-ons, and meals on the product selection page.
3. Click **Show Details** to view a cost breakdown in the pop-up window.
4. Adjust selections dynamically, and the total cost updates in real-time.


## 📌 Future Enhancements
- Improve UI with **Material UI or Tailwind CSS**.
- Add **backend integration** for saving user selections.
- Implement **user authentication** for a personalized experience.

## 📜 License
This project is open-source.

---
💡 **Happy Coding!** 🚀

