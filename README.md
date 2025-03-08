# submission_airdataqualiity

## DICODING DASHBOARD AIR DATA QUALITY
# SETUP ENV - ANACONDA
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

# SETUP ENV - SHELL/TERMINAL
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

# RUN STEAMLIT APP
streamlit run dashboard.py
