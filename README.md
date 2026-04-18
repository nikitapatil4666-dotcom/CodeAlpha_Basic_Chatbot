# 🤖 Basic Rule-Based Chatbot (Python)

## 📌 Project Description
This project is a simple rule-based chatbot built using Python.
The chatbot interacts with users by taking input and responding with predefined replies based on specific conditions.

It is designed for beginners to understand basic programming concepts like conditions, loops, and functions.

---

## 🎯 Features
- Responds to basic user inputs:
  - "hello" → Hi!
  - "how are you" → I'm fine, thanks!
  - "bye" → Goodbye!
- Runs continuously using a loop
- Case-insensitive input handling
- Handles unknown inputs gracefully

---

## 🛠️ Technologies Used
- Python
- Basic programming concepts:
  - if-elif-else
  - functions
  - loops
  - input/output

---

## ▶️ How to Run the Program

1. Install Python (if not already installed)
2. Save the code in a file named chatbot.py
3. Open terminal or command prompt
4. Run the program:

python chatbot.py

---

## 💻 Code

def chatbot():
    print("Chatbot: Hello! Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        if user_input == "hello":
            print("Chatbot: Hi!")

        elif user_input == "how are you":
            print("Chatbot: I'm fine, thanks!")

        elif user_input == "bye":
            print("Chatbot: Goodbye!")
            break

        else:
            print("Chatbot: Sorry, I don't understand that.")

# Run chatbot
chatbot()

---

## 🧪 Sample Output

Chatbot: Hello! Type 'bye' to exit.
You: hello
Chatbot: Hi!
You: how are you
Chatbot: I'm fine, thanks!
You: bye
Chatbot: Goodbye!

---

## 📚 Learning Outcomes
- Understanding of basic chatbot logic
- Use of conditional statements
- Working with loops and functions
- Handling user input in Python

---

## 🚀 Future Enhancements
- Add more responses and keywords
- Use NLP libraries for smarter replies
- Build GUI version using Tkinter
- Convert into AI-based chatbot

---

## 👩‍💻 Author
Nikita N. Patil

---

## ⭐ Contribute
Feel free to fork this repository and improve the chatbot by adding new features!

# CodeAlpha_Basic_Chatbot
