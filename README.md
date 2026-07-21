# 🔐 Gerador de Senhas

Aplicação web desenvolvida com **HTML, CSS e JavaScript** para gerar senhas aleatórias, seguras e personalizáveis.

O usuário pode definir o tamanho da senha, selecionar quais tipos de caracteres deseja utilizar e visualizar a força da senha gerada através de um cálculo de entropia.

---

## ✨ Funcionalidades

- 🔑 Geração instantânea de senhas aleatórias
- 📏 Personalização do número de caracteres
- 🔠 Inclusão de letras maiúsculas
- 🔡 Inclusão de letras minúsculas
- 🔢 Inclusão de números
- ✳️ Inclusão de símbolos
- 📊 Indicador visual da força da senha
- 🧮 Estimativa do tempo necessário para quebra da senha baseada em entropia
- 📱 Interface responsiva

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (ES6)

---

## 📂 Estrutura do projeto

```text
.
├── index.html
├── style.css
├── main.js
├── unlock.svg
├── LICENSE
└── README.md
```

---

## ⚙️ Como executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/gerador-de-senhas.git
```

2. Entre na pasta:

```bash
cd gerador-de-senhas
```

3. Abra o arquivo:

```text
index.html
```

ou utilize a extensão **Live Server** do Visual Studio Code.

---

## 🚀 Como utilizar

1. Defina o número de caracteres da senha.
2. Escolha os tipos de caracteres desejados.
3. A senha será gerada automaticamente.
4. Observe o indicador de força da senha.
5. Utilize a senha gerada onde desejar.

---

## 🔒 Critérios de geração

A senha pode ser composta por:

- Letras maiúsculas (A-Z)
- Letras minúsculas (a-z)
- Números (0-9)
- Símbolos especiais

A força da senha é calculada considerando:

- Quantidade de caracteres
- Tamanho do conjunto de caracteres escolhido
- Entropia estimada da senha

---

## 📚 Aprendizados

Este projeto foi desenvolvido para praticar:

- Manipulação do DOM
- Eventos em JavaScript
- Geração de números aleatórios
- Manipulação de strings
- Estruturas condicionais
- Cálculo de entropia para senhas
- Responsividade com CSS
- Organização de código JavaScript

---

## 🚀 Melhorias futuras

- [ ] Botão para copiar a senha
- [ ] Mostrar/Ocultar senha
- [ ] Evitar caracteres repetidos consecutivos
- [ ] Garantir pelo menos um caractere de cada categoria selecionada
- [ ] Histórico das últimas senhas geradas
- [ ] Tema escuro/claro
- [ ] Animações na geração da senha
- [ ] Barra de força com pontuação (0–100)
- [ ] Geração de frases-senha (Passphrase)
- [ ] Exportação para PWA

---

## 👨‍💻 Autor

**Sérgio Calazans**

- GitHub: https://github.com/sergiocalazans
- LinkedIn: https://linkedin.com/in/sergiocalazans

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**.

Consulte o arquivo **LICENSE** para mais informações.
