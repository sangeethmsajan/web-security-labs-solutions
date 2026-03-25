## 🐍 SQL Injection Demo Script

### 📌 Purpose

This script demonstrates a basic SQL Injection attack by modifying a query parameter.

---

### ▶️ Usage

```bash
pip install requests
python exploit.py <url> <param>
```

---

### 💡 Example

```bash
python exploit.py https://lab-id.web-security-academy.net/filter category
```

---

### ⚠️ Note

* For educational purposes only
* Use only on authorized labs (e.g., PortSwigger)
* Verify results manually in browser or Burp Suite

---

### 🧠 What it shows

* How payloads are injected into HTTP requests
* How responses change after injection
