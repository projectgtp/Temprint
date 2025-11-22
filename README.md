
🧩 TEMPRINT — AI Powered Terminal Toolkit

Temprint is a next-generation command-line toolkit designed for developers, creators, automators, and Termux power users.

It includes:

⚡ Advanced print utilities

🤖 AI-powered terminal (Qwen 4B via Bytez)

📂 File management tools

🧱 Agent Project Generator 

🖥 Terminal automation

🔥 Live logo print system

📦 Ready for Termux, Linux, Windows & macOS


Temprint aims to become the most powerful AI-aided CLI toolkit ever created.


---

📦 TEMPRINT — Developer Toolbox Module

temprint is a private lightweight developer toolkit for:

🔹 Print styling (animated + static)

🔹 File tools

🔹 Terminal tools

🔹 Agent automation

🔹 AI helpers



---

⚙️ Installation (Private or public Use)

Install module:

pip install temprint

For developer (editable) mode:

pip install -e .


---

🚀 Basic Usage

✔ Print Tools

from temprint import (
    tprint, header, box, success, error, warn,
    temp_print, logo_temp_live
)

tprint("Normal print")
header("Section Title")
box("Message in a box")
success("Done!")
error("Something failed")
warn("Be careful!")

# Animated / typewriter style print
temp_print("Loading... please wait", 0.03)

# Live animated logo display (repeat, delay)
# Update on going...

Notes:

temp_print(text, delay) prints text with a typing effect
After printing, the text dusts away like Thanos erasing the Universe.

logo_temp_live animated logo system is being upgraded (on-going development).



---

✔ File Tools

from temprint import read_file, create_txt, create_py, edit_file

create_txt("hello.txt", "Hello World!")
create_py("main.py", "print('Hi')")
content = read_file("hello.txt")
edit_file("hello.txt", "Updated content")


---

✔ Terminal Tools

from temprint import (
    list_files, delete_file, rename_file,
    move_file, copy_file, change_dir, goto_sdcard
)

list_files()
rename_file("a.txt", "b.txt")
delete_file("b.txt")
move_file("test.py", "src/test.py")
copy_file("src/test.py", "copy/test.py")
change_dir("/sdcard")
goto_sdcard()


---

✔ Project Tools

from temprint import create_python_project

create_python_project("myproject")

Creates:

myproject/
 ├── main.py
 ├── README.md
 └── requirements.txt


---

✔ AI Tools

from temprint import ai_generate, ai_explain_file, ai_summarize_file

ai_generate("Make login system code")
ai_explain_file("main.py")
ai_summarize_file("largefile.py")

Powered by:

Bytez SDK

Qwen/Qwen3-4B-Instruct

Universal response parser (fixes None outputs)



---

🖥 CLI MENU

Run from terminal:

temprint

Menu:

1. Read File
2. AI Explain File
3. AI Summarize File
4. Create TXT
5. Create PY
6. Edit File
7. Create Python Project
8. List Files
9. Delete File
10. Rename File
11. Copy File
12. Move File
13. Change Directory
14. /sdcard
15. Ask AI
16. Print Tools
17. Exit


---

🧠 AI Usage

Ask AI from Python:

from temprint import ai_generate
print(ai_generate("Explain generators"))

Explain a file:

from temprint import ai_explain_file
print(ai_explain_file("script.py"))

Summarize a file:

from temprint import ai_summarize_file
print(ai_summarize_file("data.txt"))


---

🛠 Compatibility

✔ Termux (Android)
✔ Linux
✔ Windows
✔ macOS
✔ Python 3.7+


---

📄 License

MIT License

