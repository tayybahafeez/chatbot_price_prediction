# README: Chatbot for price prediction
## Overview
A Retrieval-Augmented Generation (RAG) system for handling price-specific product queries using Gemini API and LlamaIndex.

## Features
- Preprocess Excel data into structured documents.
- Query product prices using natural language.
- Error handling for unavailable or ambiguous data.

## Setup
1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
2. **API Key**: Add your OpenAI API key to `.env`:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

 **Run Application**:
   ```bash
   python app.py
   ```
3. **Query Examples**:
   - "What is the price of FFD Safety Device 5 Burner Hob?"
   - "Tell me the cost of HW100-BP14929S3."

## Example Responses
- **Exact Match**: "The price of FFD Safety Device 5 Burner Hob is 77000."
- **No Price**: "Price not available for the specified product."
- **Multiple Matches**: Lists matching products with prices.

## Future Enhancements
- Support for more query types.
- Add a web interface.


