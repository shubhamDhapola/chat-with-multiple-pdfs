# Chat with Multiple PDFs

This Streamlit application allows users to chat with multiple PDF documents. The app processes uploaded PDFs, extracts text, splits the text into manageable chunks, creates a vector store for efficient retrieval, and then uses a conversational model to answer questions based on the contents of the PDFs.

## Features

- Upload multiple PDF documents
- Extract text from PDFs
- Split text into chunks for better processing
- Create a vector store using embeddings
- Conversational AI to interact with the document content

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

    or you can create a conda environment by looking at the conda documentation.
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the root directory and add your Groq API key:
    ```plaintext
    GROQ_API_KEY=your_groq_api_key
    ```

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Upload your PDF documents in the sidebar.

4. Click the "Process" button to extract and process the text from the uploaded PDFs.

5. Ask questions in the main input box to interact with the document content.

## Project Structure

- `app.py`: The main Streamlit application script.
- `requirements.txt`: A file listing all the required Python packages.
- `.env`: A file to store environment variables (not included in the repository for security reasons).

## Example

1. **Upload PDFs**: Use the file uploader in the sidebar to upload your PDF documents.
2. **Process Documents**: Click the "Process" button to extract text and prepare for interaction.
3. **Ask Questions**: Enter your question in the text input box and get responses based on the content of the uploaded PDFs.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
