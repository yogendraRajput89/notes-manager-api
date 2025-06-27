#Notes Manager

A simple text-based Notes Manager application written in Java that allows users to:

Add notes

View saved notes

Store notes in a local file (notes.txt)

* Technologies Used*
Java

File I/O (FileWriter, FileReader, BufferedReader)
> Features >
1. Add Note
Prompts the user to enter a note.

Appends the note to notes.txt.

2. View Notes
Reads all notes from notes.txt.

Displays them with a - bullet style.

3. Exit
Closes the program.
>>> Project Structure >>>

NotesManager/
├── src/
│   └── org/
│       └── example/
│           └── NotesManager.java
├── notes.txt (generated after adding a note)
└── README.md
