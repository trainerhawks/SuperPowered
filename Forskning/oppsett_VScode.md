### Oppskrift for oppsett av intellisense
https://github.com/pybricks/support/issues/10


I VSCode, åpne en terminal og kjør

````
Set-ExecutionPolicy -Scope CurrentUser Unrestricted

python -m venv .venv
````

Svar ja på at du ønsker å bytte til ny virtual environment
Lukk  terminal og åpne igjen og forsikre deg om at terminalen er byttet til (.venv)


````
python -m pip install --upgrade pip

python.exe -m pip install -U flake8

pip install git+https://github.com/pybricks/pybricks-api@v2
````


settings.json kopieres fra https://github.com/pybricks/pybricks-api@v2
