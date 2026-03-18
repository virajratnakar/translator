# 🌐 Simple Language Translator Web App

A lightweight web-based language translator that redirects user input to Google Translate with the selected target language.

# 🚀 Features

🌍 Supports a wide range of languages

📝 User input for custom text

🔗 Redirects to Google Translate instantly

🎨 Clean and responsive UI design

⚡ Fast and simple (no backend required)

# 🛠️ Technologies Used

HTML5

CSS3

JavaScript (Vanilla)

# 📂 Project Structure
project-folder/
│── index.html   # Main application file
# ▶️ How It Works

Select a language from the dropdown menu

Enter the text you want to translate

Click the Translate button

A new tab opens with the translated result on Google Translate

# 💡 Code Explanation

The main functionality is handled by this JavaScript function:

function Translate() {
  let language = document.getElementById("languages").value;
  let words = document.getElementById("words").value;

  let url = "https://translate.google.com/?sl=en&tl=" + language + "&text=" + words + "&op=translate";
  window.open(url);
}

sl=en → Source language (English)

tl= → Target language (selected by user)

text= → User input text

# 🎨 UI Highlights

Centered form layout

Soft shadow and rounded corners

Responsive and clean design

Hover effects on button

# ⚠️ Limitations

Requires internet connection

Relies on Google Translate (no offline support)

No API integration (just redirection)

# 🔮 Future Improvements

please contribute

Add auto-detect language

Integrate Google Translate API

Add speech-to-text input 🎤

Add dark mode 🌙

Show translation inside the app instead of redirect

# 📌 Usage

Simply open the index.html file in your browser.

# 📜 License

MIT licence.
