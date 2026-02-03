# 📅 Sistema de Agendamento

Sistema de agendamento desenvolvido em **PHP**, estruturado com base no padrão arquitetural **MVC (Model–View–Controller)**.  
O projeto foi criado com foco em organização de código, separação de responsabilidades e simulação de um sistema real utilizado em contextos como clínicas, serviços ou atendimentos agendados.

---

## 🧾 Descrição do Projeto

Sistema de agendamento desenvolvido em PHP utilizando arquitetura MVC, com controle de rotas, controllers, models e views bem definidos.  
O projeto simula um cenário real de gestão de agendamentos, priorizando organização, manutenibilidade e boas práticas de desenvolvimento backend.

---

## 🚀 Funcionalidades

- Estrutura MVC bem definida
- Separação clara entre:
  - Controllers
  - Models
  - Views
- Organização de arquivos orientada a escalabilidade
- Base preparada para integração com banco de dados
- Simulação de fluxo real de agendamentos

---

## 🛠️ Tecnologias Utilizadas

- **PHP**
- **HTML5**
- **CSS**
- **MySQL** (estrutura presente na pasta `database`)
- Arquitetura **MVC (Model–View–Controller)**

---

## 📂 Estrutura do Projeto

```bash
sistema_agendamento/
│
├── database/        # Scripts ou estrutura do banco de dados
├── public/          # Arquivos públicos (index.php, assets, etc.)
├── src/
│   ├── config/      # Configurações do sistema
│   ├── controllers/ # Lógica de controle
│   ├── models/      # Regras de negócio e acesso a dados
│   └── views/       # Interfaces e páginas
└── README.md
```

---

## ▶️ Como Executar o Projeto

### Pré-requisitos
- PHP instalado (>= 7.x)
- Servidor local (XAMPP, WAMP, Laragon ou similar)
- MySQL (caso utilize banco de dados)

### Passos para execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/oliviorui/sistema-agendamento.git
   ```

2. Mova o projeto para a pasta do servidor local  
   Exemplo usando XAMPP:
   ```bash
   htdocs/sistema-agendamento
   ```

3. Configure o banco de dados:
   - Utilize os arquivos disponíveis na pasta `database`
   - Ajuste as credenciais de conexão em `src/config`

4. Acesse o sistema no navegador:
   ```
   http://localhost/sistema-agendamento/public
   ```

---

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo:

- Consolidar conhecimentos em **PHP backend**
- Aplicar arquitetura **MVC** na prática
- Simular um sistema funcional próximo de cenários reais
- Servir como projeto de estudo e portfólio profissional

---

## 🧭 Possíveis Melhorias Futuras

- Autenticação e gestão de usuários
- Validação de dados no backend
- Interface mais moderna (UI/UX)
- API REST
- Controle de permissões
- Testes automatizados

---

## 🔓 Visibilidade do Repositório

**Status recomendado:** **Público**

**Justificativa:**
- Não contém chaves sensíveis
- Não expõe variáveis de ambiente críticas
- Código organizado e legível
- Boa demonstração de conhecimento em PHP e MVC
- Adequado para portfólio profissional

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**.
