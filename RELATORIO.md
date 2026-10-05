# Relatório de aprendizagem — GitHub Pages

**Aluna:** Anna  
**Disciplina:** Desenvolvimento Web I  
**Tema do site:** Nyan Cat  
**Ano:** 2026

## 1. Ideia do site

Escolhi fazer uma página sobre Nyan Cat porque é um tema que combina com coisas que eu gosto: internet, memes, gatos e uma estética colorida e divertida. Também achei que seria um tema fácil de transformar em uma página visualmente interessante sem precisar usar JavaScript.

A ideia foi fazer uma página simples, com uma introdução, algumas curiosidades e uma explicação de por que escolhi o tema.

## 2. Como comecei

Primeiro organizei o conteúdo que eu queria colocar na página. Depois criei o arquivo `index.html` e separei a página em partes usando elementos como `header`, `nav`, `main`, `section` e `footer`.

Depois criei o `style.css` para cuidar da aparência. Usei principalmente cores escuras com roxo e detalhes coloridos para lembrar o estilo do Nyan Cat.

## 3. HTML

No HTML aprendi melhor a importância de organizar o conteúdo em partes. Também usei links internos no menu, apontando para os `id` das seções.

Um exemplo é o menu com links para `#sobre`, `#curiosidades` e `#por-que`.

## 4. CSS

No CSS pratiquei coisas como:

- cores e fundos;
- tamanhos de fonte;
- espaçamento;
- bordas arredondadas;
- `display: grid`;
- `position`;
- `@media` para deixar a página melhor em telas menores;
- criação de um desenho simples usando elementos HTML e CSS.

A parte do desenho do Nyan Cat foi feita sem imagem externa, usando formas criadas no próprio CSS.

## 5. Git e GitHub

Para versionar o projeto, a ideia é criar um repositório no GitHub e adicionar os arquivos do site. Os principais comandos pesquisados foram:

```text
git init
git add .
git commit -m "Cria página inicial"
git add .
git commit -m "Adiciona estilos do site"
git push
```

Os commits são separados por mudanças para facilitar a identificação do que foi alterado.

## 6. GitHub Pages

O GitHub Pages permite publicar arquivos estáticos de um repositório como uma página acessível pela internet.

Depois de enviar o projeto para o GitHub, é necessário entrar nas configurações do repositório, encontrar a parte de Pages e escolher a origem da publicação. O arquivo principal deve ser o `index.html`.

Depois da publicação, o endereço fornecido pelo GitHub Pages pode ser aberto em uma aba anônima ou em outro navegador para testar se está público.

## 7. Organização dos arquivos

A organização utilizada é:

```text
nyan-cat-github-pages/
├── index.html
├── style.css
├── README.md
└── RELATORIO.md
```

O `index.html` é a página principal, o `style.css` contém os estilos e os arquivos Markdown servem para documentação do projeto.

## 8. O que aprendi

Com esse trabalho entendi melhor como HTML e CSS se juntam para formar uma página completa. Também aprendi que publicar um site é diferente de apenas abrir um arquivo HTML no computador, porque é necessário colocar os arquivos em um serviço de hospedagem.

Também passei a entender melhor a função do Git, dos commits e do GitHub Pages.

## 9. Ferramentas utilizadas

Usei um editor de código para escrever os arquivos, o Git para versionamento e o GitHub para armazenar o repositório e publicar a página.

As pesquisas foram feitas principalmente nas documentações oficiais indicadas no enunciado, especialmente a documentação do GitHub Pages e referências de HTML e CSS.

## 10. Conclusão

O resultado foi uma página estática simples sobre Nyan Cat, feita somente com HTML e CSS. O principal objetivo foi entender o processo completo: criar os arquivos, organizar o código, versionar as mudanças e publicar o resultado usando GitHub Pages.
