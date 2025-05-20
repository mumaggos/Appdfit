# Fitness App (Flask)

API de um app de fitness desenvolvida com Flask.

## Deploy no Render

1. Cria conta em https://render.com e liga ao GitHub.
2. Faz fork ou envia este projeto para o teu GitHub.
3. Cria um novo Web Service:
   - **Start command:** `gunicorn -w 4 -b 0.0.0.0:10000 src.main:app`
   - **Build command:** automático
4. Define as variáveis de ambiente do `.env.example`
5. Cria um banco MySQL no Render e roda `criar_base_dados.sql`

A app será publicada em: `https://teu-app.onrender.com`
