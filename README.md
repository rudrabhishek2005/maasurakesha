# 🌸 Motherly Nest Care - Pregnancy & Postpartum Support Platform

**Motherly Nest Care** is a comprehensive, AI-powered web application designed to support women during pregnancy and postpartum. This platform offers health tracking, emotional well-being tools, emergency assistance, and more — all with a beautiful, responsive, and accessible design.

## 🌟 Key Features

- 🤖 **AI Assistant**: Smart virtual assistant for health questions and guidance.
- 👶 **BabyCare & Growth Tracking**: Monitor baby development with visual graphs and data tracking.
- 📅 **Doctor Appointments & Calendar**: Schedule, manage, and receive reminders for appointments.
- 🏥 **Hospitals & BloodBanks**: Find nearby hospitals and blood banks using Azure Maps.
- 🎙️ **Emergency Recordings**: Voice alerts and recordings in critical situations.
- 🧘‍♀️ **Exercises & FirstAid**: Guided postnatal exercises and emergency protocols.
- 🩺 **HealthcarePro**: Connect with healthcare professionals.
- 🧾 **Landing & Login Pages**: Smooth onboarding and authentication.

## 🏗️ Project Structure

src/
├── components/ # Reusable UI components
├── config/ # App configuration
├── context/ # Global context/state management
├── data/ # Static or seed data
├── hooks/ # Custom React hooks
├── integrations/ # API/service integrations
├── lib/ # Utilities and helper functions
├── pages/ # Page-level components and routes
│ ├── auth/ # Authentication pages
│ ├── *.tsx # Feature-specific pages

markdown
Copy
Edit

## 🛠️ Tech Stack

- **Frontend**: React + TypeScript
- **Styling**: Tailwind CSS
- **Voice & AI**: Azure Cognitive Services, OpenAI
- **Emergency Services**: Twilio SMS, Call APIs
- **Mapping**: Azure Maps
- **Authentication**: Firebase/Auth0 (add details if used)

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/motherly-nest-care-main.git
   cd motherly-nest-care-main
Install dependencies

bash
Copy
Edit
npm install
Set up environment variables
Create a .env file in the root and add:

env
Copy
Edit
NEXT_PUBLIC_MAPS_KEY=your_azure_maps_key
NEXT_PUBLIC_TWILIO_SID=your_twilio_sid
NEXT_PUBLIC_TWILIO_AUTH=your_twilio_auth_token
OPENAI_API_KEY=your_openai_key
Run the development server

bash
Copy
Edit
npm run dev
📦 Deployment
Supports deployment on Vercel, Netlify, or Azure Web Apps. Make sure environment variables are configured in the deployment dashboard.

🧠 Future Enhancements
Multilingual Support

IoT Integration for Health Monitoring Devices

AR/VR Guided Meditation or Exercises

Mental Health Journal & Chatroom

👩‍💻 Contributors
Rudrabhishek – Frontend Developer & AI Integration

[Add more contributors as needed]

📄 License
This project is licensed under the MIT License.
