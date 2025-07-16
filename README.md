# sentiment_analysis_excel
Excel-based sentiment analysis of clothing product reviews using NLP techniques.

Sentiment Analysis on Customer Reviews (Excel NLP Project)

This project demonstrates a simple but effective approach to sentiment analysis using Microsoft Excel. It analyzes customer reviews of a clothing product to determine whether the sentiment is Positive, Negative, or Neutral using basic Natural Language Processing (NLP) techniques.

---

Project Overview

- Collected customer review data
- Cleaned and preprocessed the text (removing punctuation, converting to lowercase)
- Tokenized reviews into words
- Counted word frequencies
- Built a Term-Document Matrix (TDM) to map important keywords
- Assigned sentiment labels based on keyword presence
- Summarized insights for quick understanding

All steps are fully documented in the Excel file.

---

📂 What's Included

The Excel workbook contains these sheets:

| Sheet Name      | Description                                                           |
|------------------|----------------------------------------------------------------------|
| REVIEWS_Data     | Raw reviews + cleaned text (punctuation removed, lowercased)         |
| Tokenization     | Split reviews into individual words (tokens)                         |
| Tokens           | List of all extracted words                                          |
| Word_frequency   | Frequency count of specific words used across all reviews           |
| TDM              | Term-Document Matrix with sentiment classification (Positive/Negative/Neutral) |
| Insights         | Project summary and sentiment findings                               |

---

🎯 Use Cases

✅ Quickly analyze customer sentiment about products  
✅ Demonstrate NLP basics without coding  
✅ Foundation for more advanced machine learning models  

---

👩‍💻 Tools Used

- Microsoft Excel
- Manual NLP preprocessing techniques

---

✅ How It Works

1. Load raw customer reviews into Excel  
2. Clean the text (lowercase conversion, punctuation removal)  
3. Tokenize reviews into individual words  
4. Count frequency of sentiment-laden words  
5. Build a Term-Document Matrix (TDM) mapping keywords to reviews  
6. Assign sentiment labels based on positive/negative word counts  
7. Summarize results for easy interpretation

---

📈 Example Insight

- Reviews with more positive keywords (e.g., "amazing", "excellent") were labeled **Positive**
- Reviews with negative words (e.g., "poor", "worst") were labeled **Negative**
- Mixed or neutral reviews were labeled **Neutral**

---

How to Use This Repo

1. Download or clone the repo
2. Open the Excel file (`Sentiment_Analysis_Project.xlsx`)
3. Explore each sheet to see the full workflow
4. Adapt it to your own product review data

---

Future Improvements

- Automate in Python using pandas and scikit-learn
- Add advanced NLP techniques (TF-IDF, sentiment lexicons)
- Visualize sentiment distribution with charts

---

 Author

Swathi Bonagiri
