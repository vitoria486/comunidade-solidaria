---
README.md
---

# Comunidade Solidária

Sistema web desenvolvido como parte do Projeto Integrador de Tecnologia da Informação II - UFMS, com o objetivo de ajudar trabalhadores autônomos a divulgarem seus produtos e serviços de forma simples e acessível.

## 💡 Objetivo
Promover a inclusão digital por meio de uma plataforma intuitiva, permitindo que profissionais autônomos cadastrem e divulguem seus trabalhos online.

## 🛠️ Tecnologias Utilizadas
- HTML5, CSS3, JavaScript
- Firebase (autenticação e banco de dados)
- SQL (modelagem e manipulação de dados)
- Git e GitHub para controle de versão

## 🗂️ Estrutura do Repositório
```
comunidade-solidaria/
├── sql/
│   ├── schema.sql
│   ├── inserts.sql
│   ├── consultas.sql
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── README.md
├── .gitignore
```

## 🔄 Comandos Git Sugeridos
```bash
# Clonar o repositório
$ git clone https://github.com/vitoria486/comunidade-solidaria.git

# Criar nova branch para desenvolvimento de funcionalidade
$ git checkout -b feature/cadastro-usuario

# Adicionar mudanças
$ git add .

# Commitar com mensagem clara
$ git commit -m "feat: adicionar página de cadastro de usuário"

# Enviar para o repositório remoto
$ git push origin feature/cadastro-usuario
```

## ✍️ Autoria
Vitória Parpinelli — UFMS — 2025.1

---
.gitignore
---

# Ignorar arquivos de ambiente
.env

# Ignorar diretórios de dependências
node_modules/

# Ignorar arquivos de log
*.log

# Ignorar arquivos do sistema operacional
.DS_Store
Thumbs.db

# Ignorar arquivos temporários de IDEs
.vscode/
.idea/
*.swp

# Ignorar backups e arquivos sensíveis
*.bak
*.old
*.tmp

# Ignorar arquivos gerados por build (se aplicável)
dist/
build/
