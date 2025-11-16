# eduagent-capstone
AI-powered agents that tackle problems in education. Capstone project submission
EduAgent: Agents That Tackle Problems in Education

Overview
EduAgent is a modular AI system designed to address key challenges in education through intelligent, adaptive agents. It empowers students and educators by delivering personalized learning experiences, multilingual support, and automated teaching assistance.
This project was developed as part of a Capstone submission for the Kaggle Competitions platform under the “AI for Social Good” track.

Project Components
1. LearnMate (Personalized Learning Agent)
- Recommends content based on student performance and preferences
- Uses reinforcement learning to optimize learning paths
- Provides quizzes and feedback in real time
2. PolyLingua (Multilingual Support Agent)
- Translates educational content using transformer-based models
- Offers voice narration and subtitle generation
- Supports low-resource languages and dialects
3. MentorBot (Teacher Assistant Agent)
- Automates grading and feedback generation
- Summarizes student submissions
- Suggests differentiated instruction strategies

📂 Repository Structure
EduAgent/
│
├── LearnMate/
│   ├── model/
│   ├── data/
│   └── train_learnmate.py
│
├── PolyLingua/
│   ├── translation/
│   ├── speech/
│   └── polylingua_pipeline.py
│
├── MentorBot/
│   ├── feedback/
│   ├── grading/
│   └── mentorbot_utils.py
│
├── notebooks/
│   ├── demo_learnmate.ipynb
│   ├── demo_polylingua.ipynb
│   └── demo_mentorbot.ipynb
│
├── requirements.txt
├── README.md
└── LICENSE



📊 Datasets Used
- EdNet – Student interaction data
- SQuAD – QA fine-tuning
- TED Talks Translations – Multilingual training

🛠️ Installation
git clone https://github.com/yourusername/eduagent.git
cd eduagent
pip install -r requirements.txt



🧪 Running the Agents
LearnMate
python LearnMate/train_learnmate.py


PolyLingua
python PolyLingua/polylingua_pipeline.py


MentorBot
python MentorBot/mentorbot_utils.py



📈 Results

Agent		    Metric				            Performance
LearnMate	  Quiz score improvement		18%
PolyLingua	BLEU score (translation)	34.2
MentorBot	  Grading time reduction		-60%





🌍 Social Impact
EduAgent supports equitable access to quality education by:
- Personalizing learning for diverse student needs
- Bridging language gaps
- Reducing teacher workload

📜 License
This project is licensed under the MIT License.


