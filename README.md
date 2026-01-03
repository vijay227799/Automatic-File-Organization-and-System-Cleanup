# Automated File Organization and Cleanup System

An **RPA-based solution** built using **UiPath Studio** to automatically classify, archive, and clean up files in designated folders.

---

## 📌 Project Overview
In today’s digital environment, folders like **Downloads** or **Project Files** quickly become cluttered with documents, spreadsheets, images, archives, and temporary files. Manual cleanup is repetitive, error-prone, and inefficient.

This project introduces an **Automated File Organization and Cleanup System** that:
- Classifies files by extension
- Handles duplicates safely
- Archives unused files (older than 30 days)
- Deletes junk files (e.g., `.tmp`, `.log`)

---

## ✨ Features
- **Automatic File Classification**  
  Sorts files into categories: Docs, Reports, Images, Miscellaneous.
- **Dynamic Folder Creation**  
  Creates target folders if they don’t exist.
- **Duplicate File Handling**  
  Renames duplicates with suffixes like `file(1).pdf`.
- **Cleanup & Archiving**  
  Moves unused files (>30 days) to Archive.
- **Junk File Deletion**  
  Removes temporary files (`.tmp`, `.log`, `.bak`).
- **Scalable & Adaptable**  
  Easily extendable to new file types or organizational use.

---

## 🛠️ Tech Stack
- **UiPath Studio** – Workflow design and automation
- **UiPath Robot** – Workflow execution


---

## ⚙️ Requirements

### Software
- UiPath Studio
- UiPath Robot
- UiPath Activities: `Assign`, `CreateFolder`, `ForEachFile`, `MoveFile`, `DeleteFile`

---

## 🚀 Methodology
1. **Initialize** source and destination folders (Docs, Reports, Images, Archive, Miscellaneous).  
2. **Create** missing destination folders.  
3. **Iterate** through files in source folder.  
4. **Classify** files by extension and move them.  
5. **Handle duplicates** by renaming with suffixes.  
6. **Archive** files unused for >30 days.  
7. **Delete** junk files (`.tmp`, `.log`, `.bak`).  
8. **Exception Handling** with Try-Catch blocks for errors.  

---

## 📊 Results
- Accurate classification of files into categories  
- Successful archiving of unused files  
- Clean and organized folder structure  
- Improved efficiency and reduced manual workload  
