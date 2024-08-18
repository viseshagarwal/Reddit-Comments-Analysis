# Reddit Comments Analysis

---
This project involves analyzing comments from Reddit using Python. The analysis focuses on text pre-processing and various text analysis techniques to gain insights from Reddit data.

## Steps to Run the Analysis

## 1. **Clone the Repository**:
   ```bash
   git clone https://github.com/viseshagarwal/Reddit-Comments-Analysis.git
   cd Reddit-Comments-Analysis
   ```

## 2. **Set Up Your Environment**:
   - Ensure you have Python installed.
   - Install the necessary libraries:
     ```bash
     pip install -r requirements.txt
     ```

## 3. **Setting Up a Reddit Developer Account**:

To run the Reddit analysis, you'll need to set up a Reddit developer account and create an application to obtain the necessary API credentials. Follow these steps:

   ### 3.1. **Create a Reddit Account**:
   - If you don't have a Reddit account, go to [reddit.com](https://www.reddit.com) and sign up for a new account.

   ### 3.2. **Create a Reddit Application**:
   - After logging in, navigate to [Reddit's app preferences](https://www.reddit.com/prefs/apps).
   - Scroll down to the **Developed Applications** section and click on **Create App** or **Create Another App**.
   - Fill out the form with the following details:
     - **App name**: Give your application a name (e.g., "Reddit Comments Analysis").
     - **App type**: Select **script**.
     - **Redirect URI**: Enter `http://localhost:8000` (or any valid URI).
     - **Description**: (Optional) Describe your application.
   - After filling out the form, click on **Create App**.

   ### 3.3. **Obtain the Credentials**:
   - Once the app is created, you will see the **Client ID** (just under the app name) and **Client Secret** (next to the "secret" label).
   - Note down these values, along with your **Reddit username** and **password**.

   ### 3.4. **Update Credentials in the Jupyter Notebook**:
   - Open the Jupyter Notebook file (`Reddit_Analysis.ipynb`).
   - Locate the section where the credentials are defined.
   - Replace the placeholders with your actual credentials:

     ```python
     client_id = 'YOUR_CLIENT_ID'
     client_secret = 'YOUR_CLIENT_SECRET'
     user_agent = 'YOUR_APP_NAME by /u/YOUR_REDDIT_USERNAME'
     username = 'YOUR_REDDIT_USERNAME'
     password = 'YOUR_REDDIT_PASSWORD'
     ```

   ### 3.5. **Save the Notebook**:
   - After updating the credentials, save the notebook to ensure the changes are applied.


## 4. **Run the Jupyter Notebook**:
   - Open the Jupyter Notebook file (`2347164_ETE3.ipynb`).
   - Update the credentials as per your Reddit application in the appropriate cells.
   - Execute the notebook cells to start the analysis.

## 5. **Analyze the Output**:
   - The analysis output will be generated as a PDF file or other specified formats.
   - Check the `Output.pdf` for the detailed results and insights obtained from the Reddit comments.
