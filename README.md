## Hi there 👋

<!--
**nivedithan97/nivedithan97** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
```python
class tech_enthusiast_intro:
    def __init__(self):
        self.name = 'Niveditha Nagasubramanian'
        self.location = f'Singapore 🇸🇬'
        self.occupation = 'Data & AI Consultant'

        self.education = [
        {'Degree': 'Master of Business Analytics', 'Institution': 'Melbourne Business School', 'Location': 'Melbourne, Australia'},
        {'Degree': 'Bachelor of Computer Science and Bachelor of Commerce Specialist', 'Institution': 'Monash University', 'Location': 'Melbourne, Australia'}
        ]

        self.fields_of_interests: ['Data Science', 'Machine Learning & AI', 'Marketing Analytics', 'Predictive Analytics']

        self.goals_2025 =  ['Stay consistent with learning new technologies and complete at least one project every month... starting now 💪🏽 (no more procrastination!)']
        

    #display the introduction
    def display_intro(self):
        print(f"👋 Hello, I'm {self.name}!")
        print(f"\n📍 Currently located in: {self.location}")
        print(f"\n💼 Current occupation: {self.occupation}")
        print("\n🏫 Education: ")
        for edu in self.education:
            print(f"  - {edu['Degree']} from {edu['Institution']} in ({edu['Location']})")
        print("\n🔬 Fields of Interest: ")
        for interest in self.fields_of_interest:
            print(f"  - {interest}")
        print(f"\n🎯 2025 Goals: {self.goals_2025}")
    

niveditha_intro = tech_enthusiast_intro()
niveditha_intro.display_intro()
