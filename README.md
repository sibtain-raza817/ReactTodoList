# React + Vite

# 📝 React Todo List App

A simple and responsive **Todo List Application built using React JS, Context API, and Tailwind CSS**.

This project allows users to manage daily tasks efficiently with features like adding, editing, completing, and deleting todos.

---
Images:-
![image alt](https://github.com/sibtain-raza817/ReactTodoList/blob/22c1a65ee8a4ad9160900bce732649f53f5945d4/image1.png)
![image alt](https://github.com/sibtain-raza817/ReactTodoList/blob/127e4d3cd3bd199dddf36659405760d99b669e33/image2.png)



## 🚀 Features

- ➕ Add new todos
- ✏️ Edit existing todos
- ✅ Mark tasks as completed
- ❌ Delete tasks
- 🎨 Dynamic UI styling based on task status
- 🌍 Global state management using Context API
- ♻️ Reusable React components
- 📱 Responsive and clean UI

---

## 🛠️ Tech Stack

- **React JS**
- **Context API**
- **Tailwind CSS**
- **JavaScript (ES6+)**

---

## 📂 Folder Structure

```bash
src/
│
├── components/
│   ├── TodoForm.jsx
│   ├── TodoItem.jsx
│   └── index.js
│
├── context/
│   ├── TodoContext.js
│   └── index.js
│
├── App.jsx
├── main.jsx



📌 Components Explanation
🔹 TodoForm

This component is responsible for:

Taking input from user
Adding a new todo
Clearing input field after submission
🔹 TodoItem

This component handles:

Displaying todo items
Editing existing todo
Saving updated todo
Marking todo as completed
Deleting todo
🔹 TodoContext

This manages global todo state using:

addTodo()
updateTodo()
deleteTodo()
toggleComplete()
⚙️ How It Works
➕ Add Todo

Enter your task in the input field and click Add.

✏️ Edit Todo

Click the edit button (✏️) to update task text and save using 📁.

✅ Complete Todo

Use the checkbox to mark task as completed.

❌ Delete Todo

Click the delete button to remove the task.

🎯 What I Learned

This project helped me understand:

React functional components
Props
useState
useContext
Context API
CRUD operations
Reusable component design
Tailwind CSS styling
UI state handling
📸 Screenshot

Add your project screenshot here after uploading image in repo.



Follow these steps to run the project locally:

git clone https://github.com/your-username/react-todo-list.git
cd react-todo-list
npm install
npm run dev
🌟 Future Improvements

Planned features for next version:

💾 Local Storage support
🌙 Dark mode
🔍 Filter completed and pending todos
📅 Due date support
🎯 Drag and drop sorting
📊 Progress tracker
🙌 Author

Sibtain Raza

Made with ❤️ using React JS


