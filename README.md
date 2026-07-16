# 🎓 Sistema de Gestão Escolar

---

# 📖 Descrição

O **Sistema de Gestão Escolar** é uma aplicação desenvolvida com o objetivo de informatizar e centralizar os processos administrativos de uma instituição de ensino.

O sistema permite o gerenciamento de professores, disciplinas, semestres letivos, cronogramas acadêmicos, feriados e emissão de relatórios, tornando os processos mais rápidos, seguros e organizados.

---

# 🎯 Objetivo do Sistema

Desenvolver um sistema capaz de auxiliar a administração escolar na organização das informações acadêmicas, reduzindo processos manuais, evitando erros operacionais e facilitando a tomada de decisões.

Os principais objetivos são:

- Centralizar informações acadêmicas;
- Automatizar processos administrativos;
- Gerar cronogramas automaticamente;
- Emitir relatórios gerenciais;
- Melhorar a organização da instituição.

---

# 👥 Público-alvo

O sistema foi desenvolvido para ser utilizado por:

- Administradores da escola;
- Coordenação pedagógica;
- Secretaria escolar.

---

# 🏢 Tipo de Sistema de Informação

O Sistema de Gestão Escolar pode ser classificado como:

- **SIG (Sistema de Informação Gerencial)**

Também possui características de:

- ERP (integra diversos setores administrativos)
- SPT (automatiza operações rotineiras)

---

# 🔍 Problema

Muitas escolas ainda realizam diversos processos de forma manual, utilizando planilhas e documentos físicos.

Isso ocasiona problemas como:

- perda de informações;
- retrabalho;
- conflitos de horários;
- dificuldade para emissão de relatórios;
- baixa produtividade administrativa.

O sistema busca resolver esses problemas por meio da informatização dos processos.

---

# 📋 Técnicas de Levantamento de Requisitos

Durante o levantamento de requisitos foram utilizadas as seguintes técnicas:

---

## Questionário

Aplicado para validar as informações obtidas e identificar prioridades de desenvolvimento.

---

# ✅ Requisitos Funcionais

| Código | Requisito |
|----------|-----------|
| RF-01 | Permitir login no sistema |
| RF-02 | Verificar e-mail do usuário |
| RF-03 | Permitir redefinição de senha |
| RF-04 | Cadastrar professor |
| RF-05 | Editar professor |
| RF-06 | Excluir professor |
| RF-07 | Cadastrar disciplina |
| RF-08 | Editar disciplina |
| RF-09 | Excluir disciplina |
| RF-10 | Cadastrar semestre |
| RF-11 | Excluir semestre |
| RF-12 | Cadastrar feriado |
| RF-13 | Editar feriado |
| RF-14 | Excluir feriado |
| RF-15 | Gerar cronograma automaticamente |
| RF-16 | Validar conflitos de horários |
| RF-17 | Emitir relatório de disciplinas |
| RF-18 | Emitir relatório de pagamentos |
| RF-19 | Exportar relatórios para Excel |

---

# 🔒 Requisitos Não Funcionais

| Código | Requisito |
|----------|-----------|
| RNF-01 | Interface intuitiva |
| RNF-02 | Tempo máximo de resposta inferior a 3 segundos |
| RNF-03 | Sistema protegido por autenticação |
| RNF-04 | Dados armazenados com segurança |
| RNF-05 | Compatível com navegadores modernos |
| RNF-06 | Disponibilidade mínima de 99% |
| RNF-07 | Sistema responsivo |
| RNF-08 | Facilidade de manutenção |

---

# 📚 Regras de Negócio

- Apenas administradores podem acessar o sistema.
- Não pode existir dois professores cadastrados com o mesmo CPF.
- Não pode existir duas disciplinas com o mesmo nome no mesmo semestre.
- O cronograma não pode gerar conflitos de horários.
- Datas de cronograma devem respeitar os feriados cadastrados.
- Não é permitido excluir um semestre que possua cronogramas ativos.
- Relatórios somente podem ser emitidos por usuários autenticados.

---

# 📦 Escopo

## Dentro do projeto

- Login
- Recuperação de senha
- Cadastro de professores
- Cadastro de disciplinas
- Cadastro de semestres
- Cadastro de feriados
- Geração automática de cronogramas
- Emissão de relatórios
- Exportação para Excel

## Fora do projeto

- Aplicativo mobile
- Integração financeira
- Portal do aluno
- Portal do professor
- Integração com sistemas externos

---

# 📌 Premissas

- Os usuários possuem acesso à internet.
- O administrador possui treinamento básico.
- O banco de dados estará disponível durante a utilização.

---

# ⚠️ Restrições

- Projeto desenvolvido para fins acadêmicos.
- Não contempla múltiplas unidades escolares.
- Não possui integração com APIs externas.
- Não possui autenticação em dois fatores.

---

# 🔗 Matriz de Rastreabilidade

| Requisito | Origem |
|------------|--------|
| RF-01 | Entrevista |
| RF-02 | Entrevista |
| RF-03 | Entrevista |
| RF-04 | Entrevista |
| RF-05 | Entrevista |
| RF-06 | Entrevista |
| RF-07 | Questionário |
| RF-08 | Questionário |
| RF-09 | Questionário |
| RF-10 | Entrevista |
| RF-11 | Documento Escolar |
| RF-12 | Documento Escolar |
| RF-13 | Documento Escolar |
| RF-14 | Documento Escolar |
| RF-15 | Observação |
| RF-16 | Observação |
| RF-17 | Entrevista |
| RF-18 | Entrevista |
| RF-19 | Entrevista |

---

# 📐 Diagramas UML

## Diagrama de Casos de Uso

Representa as funcionalidades disponibilizadas ao administrador do sistema.

```
DiagramaCasosDeUso.png
```

---

## Diagrama de Classes

Representa as entidades do sistema, seus atributos, métodos e relacionamentos.

```
DiagramaDeClasses.png
```

---

## Diagrama de Sequência

Representa a interação entre os objetos durante os principais processos do sistema.

```
DiagramaDeSequencia.png
```

---

# 🛠 Tecnologias Utilizadas

- Draw.io
- GitHub

---

# 🚀 Fluxo Geral do Sistema

1. O administrador realiza login.
2. O sistema autentica o usuário.
3. O administrador realiza cadastros.
4. O sistema valida as informações.
5. O cronograma é gerado automaticamente.
6. O sistema verifica conflitos.
7. O administrador emite relatórios.
8. Os relatórios podem ser exportados para Excel.

---

# 📊 Funcionalidades

✔ Login

✔ Recuperação de senha

✔ Cadastro de professores

✔ Cadastro de disciplinas

✔ Cadastro de semestres

✔ Cadastro de feriados

✔ Geração automática de cronograma

✔ Validação de conflitos

✔ Relatórios

✔ Exportação para Excel

---

# 👨‍💻 Equipe

Projeto desenvolvido para a disciplina de **Análise de Sistemas**.
Vitor Chagas e Felipe Padilha
