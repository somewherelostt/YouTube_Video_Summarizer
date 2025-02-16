# 🎥 YouTube Video Summarizer with LLMs  

This project generates concise summaries of YouTube videos using Large Language Models (LLMs). It extracts video transcripts, enhances text readability, and provides structured summaries for quick understanding.  

## 🌟 Features  

✅ Extracts YouTube video transcripts  
✅ Restores punctuation with **DeepMultilingualPunctuation**  
✅ Summarizes content using **Gemini API** (Google's LLM)  
✅ Runs seamlessly in **Google Colab**  

## 🛠️ Tech Stack  

- **Google Colab** – Development environment  
- **Gemini API** – AI-powered summarization  
- **DeepMultilingualPunctuation** – Punctuation restoration  
- **YouTube Transcript API** – Transcript extraction  

## 🚀 Setup & Usage  

### 1️⃣ Clone the Repository  

```sh
git clone https://github.com/somewherelostt/YouTube_Video_Summarizer.git  
cd YouTube_Video_Summarizer
```

### 2️⃣ Install Dependencies  

```sh
pip install google-generativeai deepmultilingualpunctuation youtube-transcript-api
```

### 3️⃣ Set Up Your API Key  
>
> **Note:** The Gemini API key is not included in this repository. You will need to generate your own from [Google AI Studio](https://aistudio.google.com/).  

1. Sign in and create an API key.  
2. Add your key in the notebook where required.  

### 4️⃣ Run the Notebook  

- Open **Google Colab** and upload the `.ipynb` file.  
- Insert your **Gemini API key** where prompted.  
- Execute all cells to generate summaries.  

## 📝 Example Output  

```txt
[Video Title]: The Future of AI  
[Summary]: The video discusses AI’s role in industries like healthcare and finance, highlighting potential benefits and ethical concerns.  
```

## 📜 License  

This project is licensed under the MIT License.  

📌 **GitHub Repository:** [YouTube Video Summarizer](https://github.com/somewherelostt/YouTube_Video_Summarizer)  

---
