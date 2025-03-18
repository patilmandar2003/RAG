# 🚀 **RAG - Retrieval-Augmented Generation**

Enhance your **LangChain** applications with **debugging and monitoring** using **LangSmith**. This project provides seamless integration and setup instructions.

---

## 📌 **Setting Up LangSmith**

**LangSmith** helps in debugging and monitoring **LangChain applications** by providing tracing capabilities. To enable LangSmith tracing, set up the required environment variables.

### **🔧 Quick Setup**
Run the following commands in your terminal before executing the project:

```bash
export LANGSMITH_TRACING="true"
export LANGSMITH_API_KEY="your_api_key_here"
```

💡 **Note:** These variables will reset once you close the terminal.

---

## 🔥 **Making It Permanent**
To avoid setting the variables every time, add them to your shell configuration:

For **Bash** (`~/.bashrc` or `~/.bash_profile`):
```bash
echo 'export LANGSMITH_TRACING="true"' >> ~/.bashrc
echo 'export LANGSMITH_API_KEY="your_api_key_here"' >> ~/.bashrc
source ~/.bashrc
```

For **Zsh** (`~/.zshrc`):
```bash
echo 'export LANGSMITH_TRACING="true"' >> ~/.zshrc
echo 'export LANGSMITH_API_KEY="your_api_key_here"' >> ~/.zshrc
source ~/.zshrc
```

---

## 🛠 **Installing Dependencies**

Before running the project, ensure you have the necessary dependencies installed:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, manually install the key dependencies:
```bash
pip install langchain langchain-community langsmith
```

---

## 🎯 **Running the Project**

Once everything is set up, run your **LangChain** application with:
```bash
python main.py
```

---

## 💡 **Troubleshooting**

### **1️⃣ LangSmith API Key Not Working?**
- Ensure you have **signed up** at [LangSmith](https://smith.langchain.com).
- Copy the **correct** API key from your LangSmith dashboard.
- Set it properly in your environment variables.

### **2️⃣ Changes Not Reflecting?**
- Run:
  ```bash
  source ~/.bashrc  # For Bash
  source ~/.zshrc   # For Zsh
  ```

### **3️⃣ Common Errors & Fixes**
| Error | Possible Fix |
|--------|------------|
| `LANGSMITH_TRACING variable not set` | Run `export LANGSMITH_TRACING="true"` |
| `Command not found: langchain` | Run `pip install langchain` |
| `Permission denied when running script` | Try `chmod +x main.py` and re-run |

---

## 📜 **Contributing**
We welcome contributions! Feel free to open **issues** or submit **pull requests** to improve the project.

---

## 📄 **License**
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## ❤️ **Support & Contact**
For any questions or issues, feel free to reach out:
📧 **Email:** patilmandar2003@gmail.com  
🐙 **GitHub:** [patilmandar2003](https://github.com/patilmandar2003)  

---

### ✨ **Happy Coding! 🚀**
This version adds more structure, troubleshooting tips, and a professional touch. Let me know if you need any modifications! 😊
