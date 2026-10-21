# PugotiTasks Alexa

Integração da Alexa com a API do PugotiTasks. A skill atende na porta 3011 e precisa do PugotiTasks e do PugotiProfile para autenticação e acesso às tarefas.

## Execução

Use Node.js 20 ou o Dockerfile incluído. Configure `PUGOTITASKS_API_URL` para a API do PugotiTasks e `ALEXA_SKILL_ID` com o identificador da skill. Não inclua credenciais no repositório.

O modelo de interação em português está em `interaction-models/pt-BR.json`. A configuração de conta vinculada e OAuth encontra-se em `docs/alexa-skill.md`.
