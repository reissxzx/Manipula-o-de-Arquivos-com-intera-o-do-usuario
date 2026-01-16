# 📂 Gerenciador de Arquivos em Python (Google Colab)

Este projeto é um **gerenciador de arquivos em Python**, desenvolvido para rodar no **Google Colab**, permitindo ao usuário **criar, ler, editar, excluir e baixar arquivos** de forma simples e interativa, com proteção por senha.

O objetivo do projeto é praticar **lógica de programação**, **manipulação de arquivos**, **funções**, **tratamento de erros** e **entrada de dados do usuário**.

---

## 🚀 Funcionalidades

- 🔐 Autenticação por senha (usando `userdata` do Google Colab)
- 📄 Listagem de arquivos disponíveis no diretório
- ✍️ Escrita de conteúdo em arquivos
- 📖 Leitura de arquivos
- ➕ Adição de conteúdo sem apagar o existente
- 🗑️ Exclusão de arquivos
- ⬇️ Download de arquivos para o computador
- 🆕 Criação de novos arquivos `.txt`

---

## 🧠 Conceitos praticados

- Funções em Python
- Manipulação de arquivos (`open`, `read`, `write`, `append`)
- Estruturas condicionais (`if / elif / else`)
- Laços de repetição
- Tratamento de exceções (`try / except`)
- Uso de listas e índices
- Interação com o sistema de arquivos (`os`)
- Uso de bibliotecas externas (`google.colab.files`)

---

## 🛠️ Tecnologias utilizadas

- Python 🐍
- Google Colab
- Biblioteca `os`
- Biblioteca `google.colab.files`

---

## ▶️ Como executar o projeto

1. Abra o projeto no **Google Colab**
2. Defina uma senha usando:
   ```python
   userdata.set("FILE_PASSWORD", "sua_senha")
