# 🌐 Language Translator using NLP

##  Overview

This project implements a simple Language Translator using Natural Language Processing (NLP). It allows users to translate text from one language to another using pre-trained translation models or APIs. The system provides quick and accurate translations through a user-friendly interface.

---

##  Objectives

* Accept user input text
* Detect or select source and target languages
* Translate text using a pre-trained model/API
* Display translated output
* Provide a simple UI for interaction

---

##  Technologies Used

* Python
* NLP (Natural Language Processing)
* googletrans / transformers (pre-trained models)
* Streamlit / Flask (for UI)

---

## 📂 Project Structure

```id="b0u4xg"
task1/
│
├── translator.py        # Translation logic
│
├── templates/index.html    # HTML files (Flask)
```

---

## ⚙️ Installation

Install required libraries:

```id="4v5gqi"
pip install googletrans==4.0.0-rc1 streamlit
```

---

## ▶️ How to Run


###  Using flask

```id="k6o2sp"
python translator.py
```

Open in browser:

```id="m2b0o8"
http://127.0.0.1:5000
```

---



## 🔍 How It Works

1. User enters text
2. System sends request to translation model/API
3. Text is translated into target language
4. Output is displayed to the user

---

## 💬 Features

* Supports multiple languages
* Fast and accurate translation
* Simple user interface
* Uses pre-trained translation models

---

## 🚀 Future Enhancements

* Add voice translation
* Detect language automatically
* Use advanced models like BERT or MarianMT
* Add offline translation support

---

## 🎓 Conclusion

This project demonstrates how NLP and pre-trained models can be used to build a simple language translation system. It highlights the power of AI in breaking language barriers and enabling communication across different languages.

---

## 👨‍💻 Author

* Nischay V

---

## 📜 License

This project is for educational purposes.
