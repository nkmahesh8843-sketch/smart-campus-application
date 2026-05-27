# 🎓 Smart Campus Information System
### Python Lab Final Project — Dayananda Sagar College of Engineering

A Streamlit-based web dashboard integrating all 8 lab experiments into one complete application.

Management System

A professional Smart Campus Management System built using Python and Streamlit. This project helps manage student records, course enrollments, fee calculations, and academic analytics through an interactive web dashboard.

Features
Student academic record management
Course enrollment system
Fee calculation and tracking
Analytics dashboard with visualizations
CSV-based data storage
Streamlit interactive UI
Modular Python architecture
Project Structure
smart_campus/
│
├── app.py
├── requirements.txt
├── README.md
│
├── data/
│   ├── academic_records.csv
│   ├── courses.csv
│   ├── enrollments.csv
│   └── fees.csv
│
├── modules/
│   ├── analytics.py
│   ├── course_enrollment.py
│   ├── data_store.py
│   ├── fee_calculation.py
│   └── file_manager.py
Technologies Used
Python
Streamlit
Pandas
NumPy
Matplotlib
Requirements

Install the following dependencies:

streamlit>=1.45.0
pandas>=2.2.0
numpy>=2.1.0
matplotlib>=3.9.0
Recommended Python Version
Python 3.14.4
Installation Guide
1. Clone the Repository
git clone https://github.com/your-username/smart-campus.git
cd smart-campus
2. Create Virtual Environment (Optional but Recommended)
python -m venv venv
3. Activate Virtual Environment
Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
4. Install Dependencies
pip install -r requirements.txt
Live Demo

Visit the deployed application here:

https://smart-campus-application-by-nk.streamlit.app/
Running the Project

Run the Streamlit application:

python -m streamlit run app.py

After running, open the local URL shown in the terminal:

http://localhost:8501
Screenshots

Add your project screenshots here.

screenshots/homepage.png
Future Improvements
Firebase authentication integration
Cloud database support
AI-based analytics
Attendance management system
Mobile responsive UI
Email notifications
Contributing

Contributions are welcome.

Fork the repository
Create a new branch
Commit your changes
Push to your branch
Open a Pull Request
License

This project is licensed under the MIT License.

Author

Mahesh N K

Support

If you like this project, give it a ⭐ on GitHub.
