AWSgenAI-Bedrock
bedrock apps

![unnamed](https://github.com/user-attachments/assets/dac86bcd-02ea-4a16-8cab-91c204bfef78)

faiss-cpu in requirements.txt is used for creating vector embeddings from local env

Documents -> Split into Chunks -> Create Embedings -> Vector Store

streamlit run app.py

If you feel the pdf file you uploading is safe, then add allow_dangerous_deserialization = True in the source code faiss_index = FAISS.load_local("faiss_index", bedrock_embeddings, allow_dangerous_deserialization= True)
