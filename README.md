# AWS-Bedrock

# MedicalChatbot

The goal of the project is to create a question answer engine which can ask questions related to the pdfs uploaded.Seperate outputs from Llama2 and Claude can be accessed via Amazon Bedrock.Streamlit is used for frontend application.T

## Tech Used
1. Llama2 model
2. Claude model
3. Amazon Titan embeddings model
4. LangChain
5. FAISS
6. Streamlit
7. Python


## Run the Application

### Step 1-: Clone the Repository
```
git clone https://github.com/sunithalv/QA_AWSBedRock.git
```

### Step 2-: Create conda environment
```
conda create -p venv python==3.10 -y
```

### Step 3-: Activate Conda environment
```
conda activate venv
```

### Step 4-: Install requirements
```
pip install -r requirements.txt
```

### Step 5-: Run the application 
```
streamlit run app.py
```
