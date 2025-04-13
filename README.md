# Ai-medical-chat-bot
# AI Health Bot

## Selected Domain
AIML

## AI HEALTH BOT + MEDICAL NFT'S ON APTOS 
Healthcare systems face challenges in providing personalized, accessible medical information to patients while ensuring data security and patient privacy. Patients often struggle to understand their medical documents and diagnoses, leading to confusion, non-adherence to treatment plans, and unnecessary clinic visits. Additionally, patients lack control over their medical data, with records scattered across multiple healthcare providers.

## Abstract / Problem Description
AI Health Bot addresses the critical intersection of healthcare accessibility, data ownership, and personalized medical insights. The application serves as an AI-powered platform that allows users to upload medical documents (lab reports, prescriptions, discharge summaries) for analysis, ask questions about symptoms to receive preliminary diagnoses, and securely store medical information on blockchain technology.

By leveraging natural language processing and machine learning, AI Health Bot transforms complex medical jargon into understandable explanations tailored to user's knowledge level (healthcare professional or patient/family). The system provides personalized medical insights without replacing professional medical advice.

The blockchain integration (using Aptos) gives patients ownership of their medical data through NFT minting, ensuring that records remain secure, tamper-proof, and accessible only to authorized parties. This creates a patient-controlled medical record system that can be shared selectively with healthcare providers.

AI Health Bot employs a multi-layered approach to data security, with document encryption and secure processing, addressing concerns about medical data privacy. The application bridges the gap between advanced healthcare AI and everyday usability, making sophisticated medical insights accessible to all users regardless of technical expertise.
And it works as a virtual doctor

## Tech Stack Used
- **Backend**: Flask (Python), SQLite
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **AI/ML**: Langchain, Google Generative AI (Gemini), FAISS for vector storage
- **Blockchain**: Aptos blockchain, NFT minting capabilities
- **Document Processing**: PyPDF2, OCR (Tesseract), Document vectorization
- **Authentication**: Custom user authentication system
- **Security**: Data encryption, secure session management
- **External APIs**: Google Places API (for finding nearby hospitals)

## Project Explanation

### Core Features
1. **Symptom Analysis & Diagnosis**
   - Users can input symptoms through an intuitive interface
   - AI engine analyzes symptoms and provides preliminary diagnosis
   - Results include possible conditions with confidence levels and recommendations

2. **Medical Document Analysis**
   - Upload and analysis of various medical document formats (PDF, images, text)
   - Document vectorization for semantic search capabilities
   - Interactive Q&A interface to ask specific questions about documents

3. **Blockchain Medical Records**
   - Secure storage of medical data as NFTs on Aptos blockchain
   - Patient-controlled access to medical information
   - Immutable and verifiable medical history

4. **User Personalization**
   - Different interfaces for healthcare professionals vs. patients/family
   - Responses tailored to user type (technical for professionals, simplified for patients)
   - User account management with secure authentication

### Architecture
The AI Health Bot uses a modular architecture with several key components:

- **Diagnosis Engine**: Analyzes user-reported symptoms and generates preliminary diagnoses
- **Document Analyzer**: Processes medical documents, creates vector embeddings, and enables semantic search
- **Medical Summary Generator**: Creates comprehensive summaries from diagnostic results
- **Blockchain Integration**: Handles the minting and management of medical data NFTs
- **User Authentication**: Manages user accounts, sessions, and role-based access

### Security and Privacy
The application implements multiple security measures:
- End-to-end encryption of sensitive medical data
- Secure session management
- HIPAA-aligned data handling practices
- User consent required for all data processing

### Future Development
- Integration with electronic health record (EHR) systems
- Mobile application development
- Advanced biometric authentication
- Multi-language support
- Telemedicine integration

AI Health Bot represents a significant step toward patient-centered healthcare, combining the power of AI, secure blockchain technology, and user-friendly design to give patients better control and understanding of their health information. 

###Screenshot of project 
![WhatsApp Image 2025-04-13 at 06 11 59_01ed5bf1](https://github.com/user-attachments/assets/f9389910-e5a3-44df-8840-9b88ae0a9c0b)
![WhatsApp Image 2025-04-13 at 06 11 58_8c44c469](https://github.com/user-attachments/assets/4470ea45-d8a3-4f45-b2e7-bc0d2cb28a34)
![WhatsApp Image 2025-04-13 at 06 11 58_246a7a8b](https://github.com/user-attachments/assets/629113c2-4008-4641-ab7e-d1e972a77e06)
![WhatsApp Image 2025-04-13 at 06 11 59_6cf1fea9](https://github.com/user-attachments/assets/bbd778c7-9bff-48f7-8660-fd01c1063723)


