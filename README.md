# empresa_flask
Cadastro de empresa e funcionários (Flask + MySQL + Fetch API)

## Como rodar
1. `pip install flask mysql-connector-python`
2. Execute o arquivo `banco.sql` no MySQL (phpMyAdmin > aba SQL: copiar, colar e Executar).
   Ele cria o banco `empresa_flask`, o usuário de login e insere 5 empresas e 2 funcionários por empresa.
3. `python app.py` e abra http://127.0.0.1:5000
4. Login: `admin@teste.com` / `123456`
