# Olá, eu sou o Daniel (Kadã) Oliveira 👋

<a href="https://github.com/oliveiradniel">
  <img width="100%" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=0099F4&vCenter=true&width=820&lines=Full+Stack+Engineer+%7C+TypeScript+%C2%B7+NestJS+%C2%B7+React;AWS+Serverless+%C2%B7+Lambda+%C2%B7+DynamoDB+%C2%B7+SQS;IA+aplicada%3A+RAG%2C+LLMs+e+TensorFlow.js;%24+git+push+-u+origin+main+%F0%9F%9A%80" alt="Full Stack Engineer | TypeScript, NestJS, React, AWS Serverless e IA aplicada" />
</a>

Sou **Full Stack Engineer** e construo aplicações web de ponta a ponta, da modelagem de dados e regras de negócio até APIs e interfaces modernas. Minha stack principal é **TypeScript**, **NestJS** e **React**.

No dia a dia trabalho com:

- **Modelagem de banco de dados** em PostgreSQL, com Prisma, TypeORM ou SQL puro, e migrations versionadas
- **Autenticação e controle de acesso baseado em cargos (RBAC)**, com permissões por módulo e ação
- **Fluxos de negócio** com etapas de aprovação e notificações por e-mail
- **Front-ends em React** com TanStack (Router, Query, Table), Zustand, React Hook Form e Zod
- **Componentes documentados no Storybook** e testes com **Vitest**

Hoje estou estudando a fundo **AWS Serverless** (Lambda, API Gateway, DynamoDB, SQS, S3 e Cognito) e **engenharia de software com IA** (RAG, LLMs, MCP e agentes). Em 2026 comecei a graduação em **Ciência da Computação**.

Também presto freelances para profissionais. Gosto de atender clientes, entender o problema de cada um e apresentar soluções que façam sentido para o negócio.

<p>
  <a href="https://kadadev.com.br/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-kadadev.com.br-0099f4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio do Daniel Kadã"></a>
  <a href="https://www.linkedin.com/in/kadadniel/"><img src="https://img.shields.io/badge/LinkedIn-kadadniel-0099f4?style=for-the-badge" alt="LinkedIn do Daniel Kadã"></a>
  <a href="mailto:contatokadadev@gmail.com"><img src="https://img.shields.io/badge/Email-contatokadadev%40gmail.com-0099f4?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail do Daniel Kadã"></a>
</p>

---

## 🛠️ Com o que eu trabalho e estudo

**Front-end** &nbsp; React · Next.js · TanStack (Router, Query, Table, Start) · Zustand · React Hook Form · Zod · Tailwind CSS · shadcn/ui · Storybook

**Back-end** &nbsp; Node.js · NestJS · Express · REST · JWT e refresh tokens · OAuth · RBAC · WebSockets · noções de mensageria e microsserviços

**Dados** &nbsp; PostgreSQL · Prisma · TypeORM · SQL · DynamoDB (Single-Table Design) · Redis

**Cloud & DevOps** &nbsp; AWS (Lambda, API Gateway, DynamoDB, S3, CloudFront, SQS, SNS, Cognito, SES, CodeBuild) · Serverless Framework · Docker · Nginx · GitHub Actions

**Qualidade** &nbsp; Vitest · Jest · ESLint · Prettier · Husky · Commitlint

**IA** &nbsp; RAG · embeddings · OpenAI e Gemini · MCP · agentes · TensorFlow.js

<p>
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,vite,nodejs,nestjs,postgres,prisma,redis,aws,dynamodb,docker,githubactions,nginx,vitest,jest,tensorflow,git&perline=10" alt="Ícones das tecnologias que eu uso" />
</p>

---

## 🎓 Formação

- **Bacharelado em Ciência da Computação** · em andamento (início em 2026)
- **Engenharia de Software com IA Aplicada** · UniPDS · em andamento (LLMs, integração com APIs de IA, MCP e agentes autônomos)

---

## 🚀 Projetos em destaque

### 🥗 [Foodiary API](https://github.com/oliveiradniel/foodiary-api) · AWS Serverless + IA

API 100% serverless de um diário alimentar: o usuário envia a **foto ou o áudio** de uma refeição e a IA identifica os alimentos e calcula as calorias e os macronutrientes. Acompanha um app mobile em React Native (Expo).

- **Serverless Framework** com infraestrutura como código (CloudFormation), Node.js 24 em ARM64 e esbuild
- **Cognito** com Lambda Triggers (PreSignUp, PreTokenGeneration e CustomMessage com e-mails em React Email)
- **DynamoDB Single-Table Design** com GSI, upload seguro com **S3 Presigned POST** e entrega via **CloudFront**
- Processamento assíncrono com **SQS + DLQ** e alarmes no SNS; IA com `gpt-4.1-mini` e transcrição de áudio
- Clean Architecture: entities, use cases, controllers, gateways e validação com Zod

### ❓ LetMeAsk · IA com RAG &nbsp; [server](https://github.com/oliveiradniel/letmeask.server) · [web](https://github.com/oliveiradniel/letmeask.web)

Transforma áudios gravados em salas em conhecimento pesquisável: o áudio é transcrito por IA, vira **embeddings** e as perguntas são respondidas com **busca vetorial + geração (RAG)** a partir do conteúdo real das gravações.
`NestJS` `Prisma` `PostgreSQL` `Gemini` `React` `TanStack Query` `Web Speech API` `Docker`

### 📚 Neural Book Rec · Machine Learning &nbsp; [server](https://github.com/oliveiradniel/neural-book-rec.server) · [web](https://github.com/oliveiradniel/neural-book-rec.web)

Sistema de recomendação de livros com **redes neurais em TensorFlow.js**: feature engineering para gerar vetores de usuários e livros, treino supervisionado e predição de afinidade para recomendações personalizadas.
`NestJS` `TensorFlow.js` `Prisma` `PostgreSQL` `React` `TanStack Table`

### 🗂️ [JungleOps](https://github.com/oliveiradniel/jungleops) · Microsserviços

Gestão colaborativa de tarefas em **monorepo com microsserviços em NestJS**. Foi onde aprendi na prática **mensageria e comunicação assíncrona entre serviços**, combinadas com HTTP e **WebSockets** para notificações em tempo real, auditoria de ações e autenticação centralizada com refresh token.
`NestJS` `TypeORM` `PostgreSQL` `WebSockets` `React` `TanStack` `Docker Compose` `Nginx`

### 🌌 inOrbit · Metas semanais &nbsp; [server](https://github.com/oliveiradniel/in.orbit-server) · [web](https://github.com/oliveiradniel/in.orbit-web)

Gestão de metas com gamificação (pontos, níveis e métricas) e login via **GitHub OAuth**. API REST modular com **testes unitários e de integração** em Vitest.
`NestJS` `Prisma` `PostgreSQL` `Vitest` `React` `TanStack Router` `Docker`

<details>
<summary><b>Mais projetos</b></summary>
<br>

| Projeto | Sobre | Stack |
| --- | --- | --- |
| [api-with-cognito-and-serverless](https://github.com/oliveiradniel/api-with-cognito-and-serverless) | Fluxo completo de autenticação serverless (cadastro, confirmação, login, refresh, recuperação de senha) | AWS Cognito, API Gateway, Lambda |
| [opaque-refresh-tokens-redis](https://github.com/oliveiradniel/opaque-refresh-tokens-redis) | Rotação de refresh tokens opacos com detecção de reuso por família e scripts Lua atômicos | Node.js, Redis, Docker |
| [forgeplan-server](https://github.com/oliveiradniel/forgeplan-server) · [web](https://github.com/oliveiradniel/forgeplan-web) | Controle de estoque e planejamento de produção industrial | Quarkus, React |
| [student-classification-nn](https://github.com/oliveiradniel/student-classification-nn) | Rede neural de classificação multiclasse | Node.js, TensorFlow.js |
| [fincheck-api](https://github.com/oliveiradniel/fincheck-api) · [front](https://github.com/oliveiradniel/fincheck-frontend) | Controle financeiro pessoal | NestJS, Prisma, React |
| [waiterapp-api](https://github.com/oliveiradniel/waiterapp-api) · [web](https://github.com/oliveiradniel/waiterapp-fe) · [mobile](https://github.com/oliveiradniel/waiterapp-mobile) | Pedidos para pizzarias em tempo real (web + mobile) | Node.js, React, React Native |

</details>

---

## 📜 Certificações

<details>
<summary><b>34 certificados JStack</b> (AWS, Serverless, back-end, banco de dados e front-end)</summary>

#### ☁️ AWS & Serverless
- Introdução à AWS
- Introdução ao Serverless Framework
- Dominando o Serverless Framework
- APIs Serverless na AWS com API Gateway e Lambda Functions
- Autenticação em APIs com Serverless e AWS Cognito
- DynamoDB e Serverless Framework: o par perfeito
- Modelando tabelas no DynamoDB com Single-Table Design
- Alta performance e baixo custo com DynamoDB e Single-Table Design
- DynamoDB Single-Table Design: Relacionamentos, Paginação e Buscas
- Upload para o S3 com Lambda Functions e Presigned URLs
- S3: Mais segurança com Presigned POSTs
- Filas na AWS para Processamento Assíncrono com Lambda e SQS
- Enviando e-mails com o AWS SES
- Pipeline de CI/CD com GitHub Actions e AWS CodeBuild

#### 🔐 Back-end, autenticação e arquitetura
- Autenticação JWT em APIs Node.js
- Implementando Refresh Tokens em APIs Node.js
- Entendendo a estrutura de tokens JWT: criando a sua própria implementação
- Inversion of Control, Dependency Injection e Dependency Inversion
- 7 ferramentas para padronizar os seus projetos

#### 🗄️ Banco de dados
- Database Design: modelando bancos de dados do jeito certo
- Esqueça os ORMs: vamos falar de SQL
- SQL: Aggregate Functions, Views, Constraints e Keys
- SQL: JOINS, JSON no Postgres e Índices

#### ⚛️ Front-end
- As novidades do React 19
- Entendendo e trabalhando com o Next.js
- Renderização: CSR, SSG, SSR, ISR ou DSG
- React Query na prática
- Optimistic Updates: UIs otimistas com React Query
- Construindo tabelas com React Table (TanStack)
- Gerenciamento de estados com Zustand
- Construindo um Gerenciador de Estados do zero com React
- Autenticação com Refresh Tokens no React
- Documentando componentes com Storybook
- Preparando apps React para produção: Code Splitting, Sentry, Clarity e +

</details>

---

## 📊 GitHub Stats

<p>
  <a href="https://github.com/stats-organization/github-stats-extended">
    <img height="180" src="https://github-stats-extended.vercel.app/api?username=oliveiradniel&include_all_commits=true&show_icons=true&rank_icon=github&show=prs_merged,reviews&number_format=long&hide_border=true&bg_color=00000000&title_color=0099f4&icon_color=0099f4&text_color=8b949e" alt="Estatísticas do GitHub do Daniel Kadã" />
  </a>
  <a href="https://github.com/stats-organization/github-stats-extended">
    <img height="180" src="https://github-stats-extended.vercel.app/api/top-langs/?username=oliveiradniel&layout=compact&langs_count=6&hide_border=true&bg_color=00000000&title_color=0099f4&text_color=8b949e" alt="Linguagens mais usadas pelo Daniel Kadã" />
  </a>
</p>

<p align="center">
  <code>$ git push -u origin main</code> &nbsp;·&nbsp; sempre aprendendo e entregando 🚀
</p>
