# PromptCoder Backend

Backend do SaaS PromptCoder – geração de código a partir de prompts usando OpenAI GPT-4 Turbo.

## 🚀 Rodando localmente

1. Clone o repositório e instale as dependências:
   ```
   npm install
   ```

2. Crie o arquivo `.env` com base no `.env.example`:
   ```
   OPENAI_API_KEY=sua-chave-aqui
   PORT=4000
   ```

3. Inicie o servidor:
   ```
   npm start
   ```

## 🌐 Endpoint

**POST** `/api/generate`  
Body: `{ "prompt": "string" }`  
Resposta: `{ "code": "..." }`

---

Pronto para deploy no [Render](https://render.com) ou [Railway](https://railway.app).
