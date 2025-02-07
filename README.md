🌤 Django Weather App
A simple weather application built using Django that fetches real-time weather data for any city.

🛠 Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/yourusername/djangoweatherapp.git
cd djangoweatherapp
2️⃣ Create a Virtual Environment
sh
Copy
Edit
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows
3️⃣ Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
4️⃣ Run Migrations
sh
Copy
Edit
python manage.py migrate
5️⃣ Get a Weather API Key
Sign up at OpenWeatherMap and get an API key. Add it to your environment variables or settings.py.

6️⃣ Run the Django Server
sh
Copy
Edit
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser.
