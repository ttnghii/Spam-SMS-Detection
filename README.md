# Spam-SMS-Detection
Nowadays, the number of unwanted messages people receive on their phones is increasing. This simple project will apply machine learning techniques to automatically identify and classify text messages as either 'spam' and 'ham' (non-spam).

We attempt to build and evaluate a text classification model that is capable of distinguishing between legitimate and spam messages. By training on a labeled dataset of SMS messages, the model learns patterns and characteristics of spam content, allowing it to make accurate predictions about new and unread messages.

Our process includes:
1. Data preprocessing: Prepare raw SMS text data for analysis by cleaning, encoding, and converting them into a format suitable for machine learning.
2. Feature engineering: Extract relevant features from text data to represent the content effectively.
3. Model selection: Select the appropriate classification algorithm for the task (such as Multittinomial Naive Bayes classifier).
4. Training and evaluation: Train the selected model on a labeled dataset and evaluate the model performance using metrics: accuracy, precision, recall, and F1 score.
5. Results visualization: Visualize the model's predictions and performance metrics to better understand the model's strengths and weaknesses.

<div class="alert alert-primary d-flex align-items-center" role="alert">
  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-exclamation-triangle-fill flex-shrink-0 me-2" viewBox="0 0 16 16" role="img" aria-label="Warning:">
    <path d="M8.982 1.566a1.13 1.13 0 0 0-1.96 0L.165 13.233c-.457.778.091 1.767.98 1.767h13.713c.889 0 1.438-.99.98-1.767L8.982 1.566zM8 5c.535 0 .954.462.9.995l-.35 3.507a.552.552 0 0 1-1.1 0L7.1 5.995A.905.905 0 0 1 8 5zm.002 6a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"/>
  </svg>
  <div>
    Target:We aim to have a trained model that can efficiently classify incoming SMS messages as spam or legitimate, helping to provide users with a cleaner and safer messaging experience, filtering out unwanted and potentially harmful content.
  </div>
</div>