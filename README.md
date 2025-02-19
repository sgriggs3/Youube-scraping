# YouTube Sentiment Analysis Tool

A web application that analyzes YouTube video comments for sentiment and provides visual insights.

## Features

1. **YouTube API Integration:** Implement functions to fetch video data.
2. **Sentiment Analysis:** Implement sentiment analysis on video comments.
3. **Basic Web UI:** Create a basic user interface for input and display.
4. **API Endpoints:** Create API endpoints for data retrieval.
5. **Data Storage:** Implement basic data storage.
6. **Data Visualization Components:** Create basic charts and graphs.
7. **Web UI Integration:** Integrate visualizations into the web UI.
8. **Advanced Sentiment Analysis:** Implement more advanced NLP models and techniques.
9. **User Feedback:** Implement a user feedback mechanism.
10. **Real-Time Analysis:** Implement real-time comment analysis.
11. **Advanced Web UI Features:** Implement user authentication, configuration, and other advanced features.
12. **Testing and Deployment:** Write tests and deploy the application.

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js 14+
- YouTube API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/youtube-sentiment-analyzer.git
   ```

2. Install backend dependencies:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```

### Configuration

1. Create a `config.json` file in the project root with your YouTube API key:
   ```json
   {
     "youtube_api_key": "YOUR_API_KEY_HERE"
   }
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env
   ```

## Development

1. Start the backend server:
   ```bash
   python -m backend.app
   ```

2. Start the frontend development server:
   ```bash
   cd frontend
   npm start
   ```

## Testing

Run backend tests:
