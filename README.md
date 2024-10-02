# sms_spam_detector
This model classifies SMS text messages as either spam or ham (not spam) using a linear Support Vector Classification (SVC) model. The application will provide feedback to users, indicating whether the text is classified as spam or not, based on the model's performance.

# Features:
- Text Classification: Predicts whether an SMS message is spam or not.
- Gradio Interface: Provides a web-based user interface to input messages and receive predictions.

# Files in the Repository:
- gradio_sms_text_classification.py: The main Python script containing the code for training the model, making predictions, and launching the Gradio interface.
- SMSSpamCollection.csv: The dataset used to train the model. It contains SMS text messages and corresponding labels (spam or ham).

# How to Use the Gradio Interface:
1. Enter Text: In the input box labeled "What is the text message you want to test?", enter any SMS message.
2. Submit: Click the Submit button to classify the message as spam or ham.
3. View Result: The result will be displayed in the box labeled "Our app has determined:".
4. Flag Message: If a message is incorrectly classified, you can manually flag it using the Flag button for review.
