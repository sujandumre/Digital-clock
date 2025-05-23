🕒 Digital Clock – Python GUI Project

A simple and elegant **Digital Clock** built with Python using the `tkinter` library. The clock displays the current time in hours, minutes, seconds, AM/PM format, and also shows the date. It updates in real-time every second.



 📸 Preview

![Digital Clock Screenshot](23.png)



📁 Features

- Real-time digital clock
- Displays time in 12-hour format with AM/PM
- Displays current date
- Clean and modern GUI with `tkinter`
- Lightweight and beginner-friendly

---

 💻 Technologies Used

- Python 3.x
- Tkinter (Standard Python GUI Library)
- `time.strftime` for time formatting

---

 🚀 How to Run the Project

1. Ensure Python 3 is installed on your system.
2. Save the code into a file named `digital_clock.py`.
3. Open your terminal or command prompt.
4. Navigate to the project directory.
5. Run the script:


python digital_clock.py
🧠 Code Overview
python


📝 Explanation
strftime('%H:%M:%S %p\n%D'): Formats the time in HH:MM:SS with AM/PM and date below.

after(1000, time): Refreshes the clock every second (1000 milliseconds).

GUI created using tkinter with a custom font and background.

📂 Folder Structure

digital-clock/
├── digital_clock.py
├── README.md
└── screenshot.png (optional)

📃 License
This project is open-source and free to use under the MIT License.

🙌 Acknowledgements
Created as a beginner-friendly Python project to practice tkinter and time-based GUI applications.

