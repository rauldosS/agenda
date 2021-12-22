# Agenda

Projeto de Agenda de contatos criada utilizando Django

## 🔨 Funcionalidades

- Login
- Cadastro de usuários (formulários manuais)
- Cadastro de contatos (formulários Django)
- Visualização de contatos (pagination)
- Visualização de informações de contato individual

## 🛠️ Abrir e rodar o projeto

**Instruções necessárias para abrir e executar o projeto**

> Instale o Python 3

1. Clone o repositório e entre na pasta:
```shell
git clone https://github.com/rauldosS/agenda.git
cd agenda
```

2. Crie um ambiente virtual:
> Linux
```shell
virtualenv <nome_da_virtualenv>
```

> Windows
```shell
python -m venv <nome_da_virtualenv>
```

3. Ative o ambiente virtual que você acabou de criar:
> Linux
```shell
source <nome_da_virtualenv>/bin/activate
```

> Windows
```shell
.\<nome_da_virtualenv>\Scripts\activate
```

4. Instale os pacotes de desenvolvimento local:
```shell
pip install -r requirements.txt
```

5. Execute as migrações:
```shell
python manage.py migrate
```

Rode o servidor de desenvolvimento:
```shell
python manage.py runserver
```

### 📍 Execução no ambiente Windows
![alt text](https://github.com/rauldosS/technical-test-nexxera/blob/main/images/01.gif?raw=true)
