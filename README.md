

# PDF Chat Application 📚

A Streamlit-based web application that allows users to upload PDF documents and interact with them through a chat interface powered by Mistral AI. This application enables users to ask questions about their PDF documents and receive intelligent responses based on the document's content.

## 🌟 Features

- PDF document upload and processing
- Interactive chat interface
- Text extraction and chunking
- Vector-based document search
- Conversational memory to maintain context
- Responsive and user-friendly design
- Real-time question answering
- Support for multiple PDF uploads

## 🛠️ Technologies Used

- **Streamlit**: Web application framework
- **PyPDF2**: PDF processing
- **LangChain**: LLM framework for chat functionality
- **Mistral AI**: Language model for generating responses
- **Vector Store**: In-memory storage for document embeddings
- **HTML/CSS**: Custom styling for chat interface

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed on your system. Then install the required packages:

```bash
pip install streamlit pypdf2 langchain langchain_mistralai
```

### Environment Setup

1. Get your Mistral AI API key from [Mistral AI Platform](https://mistral.ai)

2. Clone the repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

3. Create a `.env` file in the project root (optional):
```
MISTRALAI_API_KEY=your_api_key_here
```

### Running the Application

1. Navigate to the project directory
2. Run the Streamlit app:
```bash
streamlit run app.py
```
3. Open your browser and go to `http://localhost:8501`

### **Test Online**

You can test the application here: [Chat with Multiple PDFs](https://chatwithmultiple-pdfs.streamlit.app/)

## 📖 How to Use

1. **Upload PDF**
   - Click on the file uploader in the sidebar
   - Select one or multiple PDF files
   - Click the "Process" button

2. **Ask Questions**
   - Wait for the PDF processing to complete
   - Type your question in the text input field
   - Press Enter to receive an answer

3. **View Responses**
   - Responses appear in a chat-like interface
   - User messages appear on the right (blue)
   - Bot responses appear on the left (grey)

## 🎨 Features Details

### PDF Processing
- Extracts text from uploaded PDFs
- Splits text into manageable chunks
- Creates vector embeddings for efficient searching

### Chat Interface
- Clean and intuitive design
- Message history preservation
- Distinct user and bot message styling
- Avatar support for both user and bot

### AI Integration
- Powered by Mistral AI's language model
- Maintains conversation context
- Provides relevant answers based on PDF content

## ⚠️ Important Notes

- Ensure your PDF files are text-based and not scanned images
- The application requires an active internet connection
- Keep your Mistral AI API key secure
- Large PDF files may take longer to process

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

v56

## 🙏 Acknowledgments

- Mistral AI for providing the language model
- Streamlit for the amazing web framework
- LangChain for the conversational AI framework


