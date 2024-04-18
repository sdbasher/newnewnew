pip install requests==2.26.0
pip install lxml
pip freeze > requirements.txt
pip uninstall requests -y
pip uninstall lxml -y
pip install -r requirements.txt
