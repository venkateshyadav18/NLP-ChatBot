
# 🧠 Text Processing Chatbot (Flask App)

This is a simple web-based chatbot built with **Flask** that allows users to input text and choose from several text processing operations. The bot returns the processed version of the input text in a live chat interface.

---

## 💡 Features

- 📝 **Lowercase Conversion**: Convert all characters in input text to lowercase.
- 🛑 **Stopwords Removal**: Remove common stopwords such as “the”, “is”, “and”, etc.
- ✂️ **Punctuation Removal**: Strip all punctuation from the text.
- 🔁 **Swap Case**: Swap lowercase letters to uppercase and vice versa.
- 🗨️ **Live Chat Interface**: Interactive Bootstrap-styled chat frontend.

---

## 📁 Project Structure

```
text-processing-chatbot/
│
├── app3.py                # Flask backend handling chat logic and processing
├── index3.html            # Frontend HTML using Bootstrap
├── WordCloud Demo.ipynb   # (Optional) Notebook for text visualization
```

---

## 🚀 How to Run Locally

1. **Clone the repository or copy files**
2. **Set up a Python environment**:

```bash
pip install flask
```

3. **Run the Flask app**:

```bash
python app3.py
```

4. **Visit in browser**:

```
http://127.0.0.1:5000/
```

---

## 🛠 Tech Stack

- **Python (Flask)** – Web framework
- **Bootstrap 5** – Responsive frontend styling
- **HTML** – Template rendering via Jinja2
- **Jupyter Notebook** – (Optional) For visualizations like word clouds

---

## 📸 UI Preview

The app uses a card-based chat layout that mimics modern messaging apps. Each message shows:
- **User input**
- **Bot response based on selected text transformation**

---

## ⚙️ Future Enhancements

- Add more NLP options (e.g., stemming, lemmatization, sentiment analysis)
- Integrate the word cloud notebook into the app
- Save chat logs to a database
