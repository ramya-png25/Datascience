# Student Performance Prediction — Interactive Demo

## What this is
A small Streamlit web app for a summer internship presentation. It trains a Random Forest classifier on **synthetic demonstration data** and lets a presenter enter sample study hours, attendance, previous marks, and assignment score to see an output.

**Important:** This is a working interactive prototype, but its model is trained on generated synthetic data, not on a verified real student dataset. Do not present the metrics as real-world performance.

## Run on your computer
1. Install Python 3.10 or newer.
2. Open a terminal in this folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start the app:
   ```bash
   streamlit run app.py
   ```
5. Open the local URL printed in the terminal (usually http://localhost:8501).

## Make a public demo link
A public URL cannot be created from this package alone. To publish it:
1. Sign in to GitHub and create a new repository.
2. Upload `app.py` and `requirements.txt`.
3. Sign in to Streamlit Community Cloud and choose **Create app**.
4. Select your repository, branch, and `app.py` as the main file.
5. Deploy and copy the public app URL into your PowerPoint.

## Presentation tip
Say: “This is an interactive prototype. For demonstration, it uses synthetic sample data. The next step is to train and validate it on an approved, real student dataset.”
