Hello World.
This is readme doc for ML Workshop
It predicts positive or negative sentiment, based on user input. 
The user input is sent to the model using fast api wrapper.

Predict url:
https://sentiment-analysis-e1bl.onrender.com/predict

Sample Postive Request:
{
  "text": "i liked the book"
}

Sample Response body:
{
  "sentiment": "positive",
  "confidence": 0.7409481081788426
}