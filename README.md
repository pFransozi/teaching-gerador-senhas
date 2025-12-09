# 🔐 Gerador de Senhas Seguras

Projeto desenvolvido em sala de aula com os alunos do 3º ano do Ensino Médio, com o objetivo de criar, passo a passo, um **gerador de senhas seguras**, explorando conceitos de HTML, CSS, JavaScript, lógica de programação e segurança digital.

## 💡 Sobre o Projeto

Ao longo das aulas, construímos uma aplicação que:
- Permite escolher o número de caracteres da senha;
- Gera senhas aleatórias com letras, números e símbolos;
- Estiliza e exibe a força da senha com uma barra visual;
- Calcula a **entropia** da senha para indicar sua imprevisibilidade;
- Compara a robustez da aplicação com outros geradores online.

## 📚 Etapas de Aprendizagem

### Aula 1 – Estrutura inicial
- Organização dos arquivos HTML, CSS e SVG
- Visualização do protótipo no Figma
- Estilização básica da página

### Aula 2 – Características da senha
- Criação de checkboxes para escolher letras, números e símbolos
- Estilização dos componentes

### Aula 3 – Barra de força da senha
- Implementação visual com CSS
- Estilização progressiva com cores para senhas fraca, média e forte

### Aula 4 – Interação com os botões
- Primeiros scripts em JavaScript
- Funções para aumentar/diminuir o número de caracteres da senha

### Aula 5 – Geração aleatória
- Geração de letras aleatórias com `Math.random()`
- Utilização de laços de repetição

### Aula 6 – Senhas complexas
- Inclusão de números e símbolos na geração
- Condicionais com base nos checkboxes marcados

### Aula 7 – Classificação da força da senha
- Lógica para aplicar estilos de força
- Uso do `classList` e boas práticas de organização de código

### Aula 8 – Entropia
- Cálculo da entropia da senha: `H = L x log₂(N)`
- Interpretação da entropia em bits
- Ajuste dinâmico da força com base no grau de incerteza

### Aula 9 – Avaliação do projeto
- Comparação com sites profissionais como [4devs](https://www.4devs.com.br/gerador_de_senha) e [Gerador de Senhas](https://www.geradordesenha.com.br/) e o [nosso](https://pfransozi.github.io/teaching-gerador-senhas/)
- Exibição textual do tempo estimado para quebra da senha por força bruta

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (DOM, eventos, funções, condicionais, laços)
- VSCode (com Live Preview)
- Figma (para o design inicial)