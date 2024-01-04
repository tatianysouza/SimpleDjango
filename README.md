# SimpleDjango - Lista de Tarefas

Este é um projeto simples de Django que implementa uma lista de tarefas com operações CRUD.

## Configuração do Ambiente

1. **Crie um ambiente virtual**:
    ```
    python3 -m venv .venv
    ```

2. **Ative o ambiente virtual**:
    - No Windows:
        ```
        .venv\Scripts\activate
        ```

3. **Instale as dependências**:
    ```
    pip install -r requirements.txt
    ```

## Configuração do Projeto

1. **Crie um arquivo .env na raiz do projeto** e adicione as seguintes variáveis de ambiente:
    ```
    SECRET_KEY=your-secret-key
    DEBUG=True ou False
    ALLOWED_HOSTS=.localhost, .herokuapp.com, .127.0.0.1
    ```

2. **Conecte o banco de dados SQLite3**:
    - As configurações do banco de dados SQLite3 já estão definidas no arquivo settings.py.

3. **Execute as migrações**:
    ```
    python manage.py makemigrations
    python manage.py migrate
    ```
    
## Executando o Projeto

Para executar o projeto, use o seguinte comando:

```bash
python manage.py runserver
```

## Uso

Depois de executar o servidor, você pode acessar a aplicação em seu navegador em `http://localhost:8000`.

A aplicação permite que você crie, leia, atualize e exclua tarefas.

## Contribuição

Contribuições são bem-vindas! Por favor, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Suporte

Se você encontrar algum problema ou tiver alguma dúvida sobre este projeto, por favor, abra uma issue no GitHub.

