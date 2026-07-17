# ⚽ Campeonato Society - Sistema de Gerenciamento de Campeonato

Sistema web desenvolvido em HTML, CSS e JavaScript para gerenciamento completo de campeonatos de futebol society.

## 📋 Funcionalidades

### 👑 Painel do Proprietário
- Login exclusivo por código de acesso.
- Cadastro de organizadores.
- Exclusão de organizadores.
- Alteração do código mestre de acesso.

---

### 🏆 Painel do Organizador
- Cadastro de times.
- Cadastro do responsável de cada equipe.
- Geração automática de código de acesso para cada time.
- Cadastro de atletas.
- Upload de foto do atleta.
- Cadastro de posição e número da camisa.
- Cadastro de partidas.
- Organização por:
  - Fase de Grupos
  - Quartas de Final
  - Semifinal
  - Disputa de 3º Lugar
  - Final
- Lançamento de:
  - Gols
  - Cartões Amarelos
  - Cartões Vermelhos
- Encerramento e reabertura de partidas.

---

### 👤 Painel do Responsável pelo Time
- Login utilizando o código de acesso do time.
- Visualização do elenco.
- Visualização de:
  - Gols
  - Cartões
  - Jogos
  - Classificação

---

## 📊 Classificações Automáticas

O sistema calcula automaticamente:

- Pontos
- Jogos
- Vitórias
- Empates
- Derrotas
- Gols Pró
- Gols Contra
- Saldo de Gols

Também gera automaticamente:

- 🥇 Artilharia
- 🟨 Ranking de Cartões

---

## 🔐 Níveis de Acesso

### Proprietário

Possui acesso total ao sistema.

Pode:

- Criar organizadores
- Alterar código de acesso do proprietário

---

### Organizador

Responsável pela administração do campeonato.

Pode:

- Criar times
- Cadastrar atletas
- Criar jogos
- Registrar súmulas
- Encerrar partidas

---

### Responsável do Time

Possui acesso apenas às informações da própria equipe.

Pode visualizar:

- Elenco
- Jogos
- Estatísticas
- Classificação

---

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Google Fonts
- Local Storage API (Storage Compartilhado)

---

## 📁 Estrutura

```
campeonato-society.html
```

Todo o projeto está concentrado em um único arquivo contendo:

- Interface
- Estilos
- Regras de negócio
- Persistência de dados

---

## 💾 Armazenamento

Os dados são armazenados utilizando um sistema de armazenamento compartilhado através da API:

```javascript
window.storage
```

São armazenados:

- Times
- Atletas
- Jogos
- Organizadores
- Configurações

---

## 📸 Cadastro de Atletas

Cada atleta pode possuir:

- Foto
- Nome
- Número
- Posição

As imagens são automaticamente redimensionadas antes de serem armazenadas.

---

## 📅 Fases Suportadas

- Fase de Grupos
- Quartas de Final
- Semifinal
- Disputa de 3º Lugar
- Final

---

## 📈 Estatísticas

O sistema contabiliza automaticamente:

- Total de gols por atleta
- Total de cartões amarelos
- Total de cartões vermelhos
- Ranking de artilheiros
- Ranking disciplinar

---

## 🎨 Interface

O sistema possui uma interface moderna inspirada em campeonatos profissionais, utilizando:

- Tons de verde
- Layout responsivo
- Cards
- Modais
- Tabelas
- Sistema de notificações (Toast)

---

## 🚀 Possíveis Melhorias Futuras

- Login com senha criptografada
- Banco de dados (MySQL/PostgreSQL)
- API REST
- Histórico completo de campeonatos
- Exportação para PDF
- Geração automática da tabela
- Mata-mata automático
- Upload de escudos dos times
- Dashboard com gráficos
- Estatísticas por campeonato
- Integração com aplicativo mobile
- Sistema de inscrições online
- Controle financeiro
- Arbitragem
- Controle de suspensão automática
- Upload de súmulas
- Transmissão ao vivo
- Área do atleta

---

## 👨‍💻 Autor

Projeto desenvolvido para gerenciamento de campeonatos de futebol society, oferecendo uma solução simples, rápida e organizada para administradores, organizadores e responsáveis por equipes.

---

## 📄 Licença

Este projeto é de uso privado. Sua utilização, modificação ou distribuição depende da autorização do autor.
