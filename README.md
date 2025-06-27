**#NotesApp – Java File I/O Based Notes Manager**

**#Description**
**NotesApp** is a console-based Java application that allows users to write, read, and delete personal notes. All notes are stored in a local text file (`notes.txt`) 
  using Java’s File I/O classes such as `FileWriter`, `BufferedReader`, and `File`. This application demonstrates basic **data persistence**, **file handling**, and **exception management**.



**Objective**
- Implement a simple notes management system.
- Practice Java File I/O with text files.
- Handle invalid input and empty file conditions gracefully.
- Build command-line interface applications with user interaction.


**Tools & Technologies**
- **Java (JDK 8 or later)** – Language used
- **VS Code / IntelliJ IDEA** – IDE for writing and compiling code
- **Terminal / Command Prompt** – For executing compiled Java files


**Project Structure**
NotesApp/
└── NotesApp.java # Main source file
└── notes.txt # File created automatically to store notes

## 🔑 Key Concepts Used

- Java File Handling (`File`, `FileWriter`, `FileReader`, `BufferedReader`)
- `try-catch` Exception Handling
- Command-line user input (`Scanner`)
- String and file validation (`file.exists()`, `file.length()`)

---

**Features**

**# 1. Write a Note**
- Appends a user note to the file.
- Automatically creates the file if not present.

**#2. Read All Notes**
- Displays all saved notes.
- Shows a friendly message if the file is missing or empty.

**#3. Delete All Notes**
- Clears the contents of the file.
- Confirms file existence and emptiness before deletion.

**#4. Exit**
- Gracefully exits the program.


**#How to Run**

1. **Compile the program**
   javac NotesApp.java
     Run the program
     java NotesApp

**Sample Output**
===== Notes App =====
1. Write a Note
2. Read All Notes
3. Delete All Notes
4. Exit
Choose an option: 1
Enter your note: Java File I/O is interesting!
Note saved successfully.

**Example Code Structure**
 1. Show menu
 2. Get user choice
 3. If choice == 1: Write note to file using FileWriter
 4. If choice == 2: Read notes using BufferedReader
 5. If choice == 3: Delete contents using FileWriter overwrite
 6. If choice == 4: Exit

**#Future Improvements**
1.Add option to delete a specific note.
2.Allow timestamping each note.
3.Export notes to PDF or HTML.
4.Add search functionality.

