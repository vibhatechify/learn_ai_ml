<!-- Backend -->
python3.10 -m venv venv -> create virtual env
source venv/bin/activate -> activate virtual env

pip install flask flask-cors flask-sqlalchemy flask-migrate python-dotenv
pip freeze > requirements.txt

pip install -r requirements.txt -> to install requirements.txt


<!-- Frontend -->
yarn create frontend
cd frontend
yarn install
npm run dev
yarn add react-router-dom axios