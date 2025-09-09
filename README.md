# Python_Django-
Instalação de ambiente virtual framework Django e primeiras práticas em aula 

No ambiente Linux
==================
# Criar o ambiente virtual
virtualenv -p python3 ambi1
source ambi1/bin/activate
pip install <<nome_do_pacote>>
# Gerar saída com as bibliotecas instaladas
pip freeze 
pip freeze > requirements.txt

# Restaurar o ambiente a partir do requirements.txt
virtualenv -p python3 venv
source venv/bin/activate

 ambiente Windows
====================
# Criar o ambiente virtual
pip install virtualenv

virtualenv ambi1
python -m virtualenv venv

cd ambi1
cd Scripts
activate.bat
cd..
cd..

pip install <<nome_do_pacote>>
# Gerar saída com as bibliotecas instaladas
pip freeze 
pip freeze > requirements.txt
