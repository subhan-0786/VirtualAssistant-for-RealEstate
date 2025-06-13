# Virtual Assistant for Real Estate

A comprehensive VR-enabled real estate solution that combines immersive virtual house tours with an intelligent voice assistant to enhance property viewing and customer interaction experiences.


## Project Overview

This project creates an innovative real estate platform that integrates:
- **VR House Models** - Immersive virtual property tours
- **Voice Assistant** - AI-powered conversational interface for property inquiries
- **3D Character Avatar** - Visual representation of the voice assistant with facial expressions and lip sync

## Features

### 🏠 VR House Experience
- Interactive virtual reality house tours
- Detailed architectural visualization
- Immersive property exploration
- Compatible with VR headsets and devices

### 🎙️ Voice Assistant
- Natural language processing for property queries
- Text-to-speech and speech-to-text capabilities
- Real estate data integration (13,034+ property listings)
- Intelligent responses using AI model inference

### 👤 3D Character Avatar
- Realistic 3D assistant representation
- Facial expressions and animations
- Lip synchronization for natural interaction
- Rigged model with blend shapes

## Technical Architecture

### Core Technologies

| Component | Technology | Purpose |
|-----------|------------|---------|
| **VR Development** | Unity 3D | Building VR house models and environment |
| **3D Modeling** | Blender | Creating detailed architectural designs |
| **Voice Assistant** | Python | AI-powered conversational interface |
| **AI Inference** | Groq API | LLM integration for intelligent responses |



### Python Libraries
- `os` - File handling and environment variables
- `csv` - CSV file operations for property data
- `numpy` - Numerical operations and array handling
- `faiss` - Fast similarity search for property matching
- `pyttsx3` - Text-to-speech conversion
- `speech_recognition` - Speech-to-text processing
- `sentence_transformers` - Sentence embeddings generation
- `groq` - AI model inference API integration

## Project Structure

```
virtual-real-estate-assistant/
├── VR-Environment/          # Unity 3D VR project files
├── Voice-Assistant/         # Python voice assistant implementation
├── 3D-Character/           # Blender 3D character models
├── Data/                   # Property dataset (text_data.txt)
├── Documentation/          # Project presentations and docs
└── README.md
```

## Data

The project utilizes a comprehensive real estate dataset containing:
- **13,034 property listings**
- **24 data columns** including:
  - Property ID, Location, Price
  - Property Type (House/Flat)
  - Area, Bedrooms, Bathrooms
  - Geographic coordinates (Latitude/Longitude)
  - Agent and Agency information
  - Price per square foot calculations

### Sample Data Structure
```
Property ID: 237062
Location: G-10, Islamabad  
Price: PKR 10,000,000
Type: Flat (2 bed, 2 bath)
Area: 4 Marla (1,089 sqft)
```


## Installation & Setup

### Prerequisites
- Unity 3D (2021.3 LTS or later)
- Python 3.8+
- VR headset (optional, VR simulator available)
- Blender 3.0+ (for 3D model editing)

### Voice Assistant Setup
```bash
pip install numpy faiss-cpu pyttsx3 SpeechRecognition
pip install sentence-transformers groq
```

### Environment Variables
```bash
export GROQ_API_KEY="your_groq_api_key"
```

## Usage

1. **Launch VR Environment**
   - Open Unity project
   - Build and run VR scene
   - Use VR headset or device simulator

2. **Start Voice Assistant**
   ```bash
   python voice_assistant.py
   ```

3. **Interact with System**
   - Navigate virtual property using VR controls
   - Ask questions about properties using voice
   - Receive responses from 3D character avatar

## Future Enhancements

- Multi-language support
- Advanced property filtering
- Integration with real estate APIs
- Mobile VR compatibility
- Cloud deployment options
- Machine learning property recommendations

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/new-feature`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/new-feature`)
5. Create Pull Request

This project is developed for educational and research purposes.

*Transforming real estate experiences through immersive VR technology and intelligent voice assistance.*
