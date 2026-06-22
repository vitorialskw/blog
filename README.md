# Ensaios

Blog minimalista para ensaios pessoais — estética renascentista, natureza, silêncio.

## Como hospedar no GitHub Pages (gratuito)

1. Crie um repositório no GitHub (pode ser público)
2. Faça upload de todos os arquivos deste projeto
3. Vá em **Settings → Pages**
4. Em *Source*, selecione `main` e pasta `/root`
5. Salve — em alguns minutos o site estará em `https://seu-usuario.github.io/nome-do-repo`

## Como adicionar um novo ensaio

1. Copie o arquivo `ensaios/sobre-a-lentidao.html`
2. Renomeie para o título do seu ensaio (ex: `ensaios/sobre-silencio.html`)
3. Edite o conteúdo dentro das tags `<main class="essay-body">`
4. Adicione uma entrada no `index.html` dentro de `.essay-list`

## Estrutura

```
blog/
├── index.html          ← página principal com lista de ensaios
├── css/
│   └── style.css       ← todo o estilo
└── ensaios/
    └── sobre-a-lentidao.html   ← exemplo de ensaio
```

## Tipografia

- **Cormorant Garamond** — títulos (carregada do Google Fonts)
- **EB Garamond** — corpo do texto

Ambas são gratuitas e de código aberto.
