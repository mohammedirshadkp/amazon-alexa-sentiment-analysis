<h1>📊 Amazon Alexa Reviews — Text Mining &amp; Sentiment Analysis</h1>
<p>
A complete Social Media Analytics project analyzing <strong>3,150 real Amazon Alexa customer reviews</strong> using NLP, sentiment analysis, topic modeling, and visualization techniques.
</p>
<p>
This repository contains the full project:
</p>
<ul>
  <li>Source code</li>
  <li>Dataset</li>
  <li>Cleaned/processed output</li>
  <li>Notebook</li>
  <li>Final report (DOCX + PDF)</li>
  <li>Visual images</li>
  <li>README documentation</li>
</ul>

<hr />

<h2>📁 Project Structure</h2>

<pre><code>SocialMediaAnalyticsProject/
│
├── Notebook/
│   └── Amazon_Alexa_Analysis.ipynb          
│
├── Dataset/
│   └── amazon_alexa.tsv                      
│
├── Report/
│   ├── Amazon_Alexa_Report.docx              
│   └── Amazon_Alexa_Report.pdf               
│
├── Images/
│   ├── wordcloud.png                         
│   ├── rating_distribution.png               
│   └── sentiment_distribution.png            
│
├── Processed_Output/
│   └── amazon_alexa_final_results.csv        
│
└── README.md                                 
</code></pre>

<hr />

<h1>📘 Project Overview</h1>
<p>
This project uses <strong>Natural Language Processing (NLP)</strong> to extract insights from Amazon Alexa customer reviews.
The analysis focuses on:
</p>
<ul>
  <li>Understanding customer sentiment</li>
  <li>Identifying frequently used words</li>
  <li>Discovering hidden discussion topics</li>
  <li>Comparing textual sentiment with rating scores</li>
  <li>Exploring customer experience patterns</li>
</ul>
<p>
This project is part of <strong>Social Media Analytics Course</strong> requirements.
</p>

<hr />

<h1>❓ Research Questions</h1>
<ol>
  <li>What is the overall sentiment of Amazon Alexa users?</li>
  <li>Which words are most frequently used in customer reviews?</li>
  <li>What topics or themes emerge from the review text?</li>
  <li>How do numerical ratings align with sentiment-based labels?</li>
</ol>

<hr />

<h1>🧠 Methods &amp; Techniques</h1>

<h2>1. Text Preprocessing</h2>
<ul>
  <li>Lowercasing</li>
  <li>Removing punctuation</li>
  <li>Removing URLs</li>
  <li>Removing repeated spaces</li>
  <li>Cleaning &amp; normalization</li>
</ul>

<h2>2. Sentiment Analysis</h2>
<p>Using <strong>VADER (NLTK)</strong>:</p>
<ul>
  <li>Generates compound sentiment score (−1 to +1)</li>
  <li>Labels each review as:
    <ul>
      <li>Positive</li>
      <li>Neutral</li>
      <li>Negative</li>
    </ul>
  </li>
</ul>

<h2>3. Word Cloud Visualization</h2>
<p>
A word cloud is generated to highlight the most dominant words across all reviews.
</p>

<h2>4. Topic Modeling</h2>
<p>Using <strong>Latent Dirichlet Allocation (LDA)</strong>:</p>
<ul>
  <li>Extracts 3 hidden topics</li>
  <li>Displays top representative keywords for each topic</li>
</ul>

<h2>5. Visual Analysis</h2>
<ul>
  <li>Rating distribution plot</li>
  <li>Sentiment distribution plot</li>
</ul>

<hr />

<h1>📊 Results Summary</h1>

<h2>Sentiment Distribution</h2>
<ul>
  <li>Majority of reviews are <strong>positive</strong></li>
  <li>Smaller proportion are neutral</li>
  <li>Very few reviews are negative</li>
</ul>

<h2>Rating Distribution</h2>
<ul>
  <li>Most users gave <strong>4-star or 5-star</strong> ratings</li>
  <li>Strong alignment with sentiment results</li>
</ul>

<h2>Word Cloud Findings</h2>
<p>Most frequently used words include:</p>
<ul>
  <li><em>love</em>, <em>great</em>, <em>use</em>, <em>easy</em>, <em>alexa</em>, <em>echo</em>, <em>sound</em></li>
</ul>

<h2>Topic Modeling (LDA)</h2>
<p>Three main topics emerged:</p>
<ol>
  <li><strong>General device functionality</strong></li>
  <li><strong>Sound/music quality</strong></li>
  <li><strong>User experience enjoyment</strong></li>
</ol>

<hr />

<h1>🧪 How to Run the Project</h1>

<h2>1. Install Required Libraries</h2>
<pre><code>pip install pandas numpy matplotlib nltk scikit-learn wordcloud
</code></pre>

<h2>2. Open the Notebook</h2>
<p>Open the following file in Jupyter or VS Code:</p>
<pre><code>Notebook/Amazon_Alexa_Analysis.ipynb
</code></pre>
<p>Run all cells using <strong>Shift + Enter</strong>.</p>

<h2>3. Output Files Generated</h2>
<ul>
  <li><code>amazon_alexa_final_results.csv</code> (processed dataset with sentiment labels)</li>
  <li>Word cloud image</li>
  <li>Sentiment distribution plot</li>
  <li>Rating distribution plot</li>
</ul>

<hr />

<h1>🖼 Visual Outputs</h1>
<p>The following visual outputs are generated and stored in the <code>Images/</code> folder:</p>
<ul>
  <li><strong>Word Cloud</strong> – Shows the most dominant words in reviews.</li>
  <li><strong>Rating Distribution</strong> – Displays how customers rated Alexa.</li>
  <li><strong>Sentiment Distribution</strong> – Compares positive, neutral, and negative sentiments.</li>
</ul>

<hr />

<h1>📄 Full Academic Report</h1>
<p>
The complete report is available in the <code>Report/</code> directory:
</p>
<ul>
  <li><code>Amazon_Alexa_Report.docx</code></li>
  <li><code>Amazon_Alexa_Report.pdf</code></li>
</ul>
<p>
The report includes:
</p>
<ul>
  <li>Introduction</li>
  <li>Methods</li>
  <li>Results</li>
  <li>Visualizations</li>
  <li>Conclusion</li>
  <li>References</li>
</ul>

<hr />

<h1>🔗 GitHub Repository Link</h1>
<p>
<a href="https://github.com/mohammedirshadkp/amazon-alexa-sentiment-analysis">
https://github.com/mohammedirshadkp/amazon-alexa-sentiment-analysis
</a>
</p>

<hr />

<h1>👨‍💻 Author</h1>
<p>
<strong>Mohammed Irshad</strong><br />
Vytautas Magnus University<br />
Social Media Analytics – Course Project
</p>

<hr />

<h1>📚 References</h1>
<ul>
  <li>
    S. Kumar et al., “Sentiment Analysis on Amazon Alexa Reviews Using NLP and Classification,” 
    ICAC3N, 2022.
  </li>
  <li>
    N. N. Vesaokar, “Sentiment Analysis of Amazon Alexa Reviews using Machine Learning,” 2023.
  </li>
  <li>
    S. A. Mostafa et al., “Classification and Sentiment Analysis of Amazon Alexa Reviews,” 2024.
  </li>
  <li>
    Y. Hao, “Using Sentiment Analysis to Predict Customer Satisfaction for Amazon Echo,” 2020.
  </li>
  <li>
    T. Escalona, “Detect Sentiment from Customer Reviews using Amazon Comprehend,” AWS ML Blog, 2018.
  </li>
</ul>

<hr />

<h1>✔ License</h1>

