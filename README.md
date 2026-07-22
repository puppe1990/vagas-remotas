# Remote Stack

Curadoria de vagas remotas de **Rails** e **Laravel** no Brasil, nearshore em dólar e projetos freelance (Upwork, Workana, Arc).

**Live:** [https://vagas-remotas.netlify.app](https://vagas-remotas.netlify.app)

## O que tem

- Filtros: Todas · Brasil · Freelance · Rails · Laravel
- Busca por empresa, cargo ou PJ
- Cards com tags, localidade, nível e link para candidatura
- Tema claro / escuro
- Links para boards externos (Remote Rocketship, Indeed, LinkedIn, etc.)

## Stack

Página estática única (`index.html`) — HTML, CSS e JavaScript vanilla. Sem build.

## Rodar local

```bash
open index.html
# ou
npx serve .
```

## Deploy

Hospedado no [Netlify](https://www.netlify.com/). Para republicar após editar:

```bash
netlify deploy --prod --dir=.
```

## Atualizar vagas

As vagas ficam no array de dados dentro de `index.html`. Edite o arquivo, teste localmente e faça deploy.

## Licença

Uso pessoal / portfólio. Vagas e links apontam para fontes externas — confira sempre a origem antes de candidatar.
