# Day 2 - Linux Learning Journey 🚀

## Repository Setup

Move to Linux journey repository:

```bash
cd LINUX-JOURNEY
```

Create Day 02 folder:

```bash
mkdir -p Day-02
```

Create notes file:

```bash
touch Day-02/day-02-linux.md
```

---

## Commands Learned Today

### touch

Create a new empty file:

```bash
touch file.txt
```

---

### cat

Display file contents:

```bash
cat file.txt
```

---

### echo

Print text or write into a file:

```bash
echo "Hello Linux"

echo "Hello" > file.txt
```

---

### rmdir

Remove empty directory:

```bash
rmdir folder_name
```

---

### head

Show first lines of a file:

```bash
head file.txt

head -5 file.txt
```

---

### tail

Show last lines:

```bash
tail file.txt
```

---

### tail -f

Monitor live file updates:

```bash
tail -f logs.txt
```

---

### less

Read large files page by page:

```bash
less file.txt
```

---

### more

Display file contents page wise:

```bash
more file.txt
```

---

### zcat

Read compressed files:

```bash
zcat file.gz
```

---

## Practice Summary

- Learned file creation using `touch`
- Displayed file contents using `cat`
- Practiced `echo`
- Removed directories using `rmdir`
- Used `head` and `tail`
- Learned live monitoring using `tail -f`
- Explored `less` and `more`
- Read compressed files with `zcat`

---

## Git Commands Used

Add files:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Day 2 Linux learning notes"
```

Push to GitHub:

```bash
git push origin main
```

---

## Folder Structure

```text
LINUX-JOURNEY/
│
├── Day-01/
│   └── day-01-linux.md
│
├── Day-02/
│   └── day-02-linux.md
│
└── README.md
```