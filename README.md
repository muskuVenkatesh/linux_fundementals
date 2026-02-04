# Linux Fundamentals Practical Assignment

This repository contains the implementation of basic Linux commands as part of the **Linux Fundamentals Practical Assignment**.  
Each task includes the **commands used** along with a **clear explanation** of what each command does.

---

## 1. Creating and Renaming Files/Directories

### Commands
```bash
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt
ls

```
## 2. Viewing File Contents

### Commands
```bash 
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

## 3. Searching for Patterns Using grep

### Command
```bash 
grep "root" /etc/passwd
```

## 4. Zipping and Unzipping Directories

### Commands 

```bash 
cd ..
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -d unzipped_dir

```

## 5.Downloading Files Using wget

### commands

```bash
wget https://example.com/sample.txt
```

## 6. Changing File Permissions

### Commands

```bash
touch secure.txt
chmod 444 secure.txt
ls -l secure.txt
```

## 7. Working with Environment Variables

### Commands

```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```





