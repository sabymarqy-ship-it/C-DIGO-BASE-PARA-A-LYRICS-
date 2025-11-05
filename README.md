# 🎓 Para a Galerinha que veio através das minhas Redes💜
## 🐍 Python: Player de Letras Sincronizado (Console)

Olá! Eu sou estudante de Python e criei este projeto como uma forma de colocar em prática meus estudos e juntar com duas coisas que eu amo, que é a música e a programação. Espero poder ajudar a tirar algumas dúvidas e contribuir com outros estudantes que nem eu 💜

Este repositório contém o código base de um **Player de Letras (Lyrics Player)**. Ele permite exibir poemas, letras de músicas, cenas de filmes, declarações ou qualquer texto escrito no terminal do VS Code, com o texto destacando-se no momento exato (o famoso "karaokê de terminal"!).

---

### 🛠️ Como Usar e Estudar (Guia Rápido)

O projeto é excelente para praticar **Sincronização de Tempo** e **Controle do Terminal** com comandos ANSI.

#### 📝 1. Adaptando o Conteúdo

Para colocar seu próprio texto (música ou poema), concentre-se na **Seção 5 (`DADOS DO CONTEÚDO`)** do código:

* **`"time"`:** Defina o *timestamp* exato (em segundos) em que a linha deve ser renderizada.
* **`"original"`:** Insira o seu texto. Use o `\n` para forçar quebras de linha manuais e ver a função `split_and_wrap_text` em ação!
* **`TOTAL_MUSIC_DURATION`:** Ajuste este valor para o tempo total de execução.

#### ✨ 2. Dicas de Customização e Solução de Problemas

* **Customização Rápida:** Para testar temas e cores diferentes, edite as variáveis de cor na **Seção 2 (`CONFIGURAÇÃO DE ESTILO`)**. Experimente!
* **Sincronia Fina:** Se o ritmo não bater com a leitura, ajuste os valores decimais (`0.1s`, `0.2s`) dos *timestamps* em `LYRICS_DATA`.
* **Problemas com Cor:** Se o código ANSI não funcionar, verifique se seu terminal (ou ambiente de execução) tem suporte completo (o VS Code Terminal geralmente funciona perfeitamente).

---

**Requisitos:** Apenas Python 3.x e um terminal que entenda comandos ANSI (como VS Code Terminal, Linux ou Mac).

Bons estudos! 🐍
