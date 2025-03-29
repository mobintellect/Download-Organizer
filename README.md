# Windows Downloads Organizer

Organizes top-level files in your Downloads folder by filetype.

## 🧠 What It Does
This Python script scans the **top-level of your Downloads folder** and:
- Sorts each file into categorized folders (PDFs, Images, Videos, 3D Prints, etc.)
- Creates a `Downloads\Organized` directory with subfolders
- Deletes extracted folders if they match archive names
- Leaves all subfolders untouched for manual review
- Logs every file moved in a timestamped log file

## 📁 Example Output
```
C:\Users\YourName\Downloads\Organized\
├── PDFs\
├── Images\
├── Archives\
├── Videos\
├── 3D Prints\
└── logfile_2025-03-28_12-00-00.txt
```

## 🔧 How to Use It
1. Make sure Python 3.6+ is installed
2. Download or clone this repository
3. Open a terminal and run:
   ```bash
   python dorg.py
   ```
4. It will:
   - Summarize how many files it found
   - Estimate how long it will take
   - Ask if you want to proceed

## 🛠 Features
- ✅ Works entirely from the top level of Downloads
- ✅ Safe duplicate handling (e.g., `file (1).pdf`)
- ✅ Automatically skips folders
- ✅ No destructive changes — folders left for you to review
- ✅ Fully timestamped logs

## 🧾 License
[MIT License](LICENSE)

## ✍️ Author
Allen (script developed with assistance from ChatGPT GPT-4)

## 💡 Original Prompt
> "I need to write a python program or script that will help me organize my folders in windows by file type. Basically what I want to do, is have the program ask me what folder I want to organize. Then, it takes that folder and moves every file even in the subfolders into a new folder named after the filetype inside."

This later evolved to focus solely on Downloads with an automated destination.

---

🗂️ Organized. Clean. Custom. Use it as often as you like.

