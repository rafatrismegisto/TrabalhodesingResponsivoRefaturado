# Agência Criativa Web — Refatorado com SASS

Projeto refatorado utilizando SASS (partials, variáveis, mixins, aninhamento) conforme requisitos do módulo.

Como usar

1. Instalar dependências:

```powershell
npm install
```

2. Compilar SASS (build):

```powershell
npm run build
```

ou para ficar em watch (recompila automaticamente):

```powershell
npm run sass
```

Estrutura

- scss/ — arquivos SASS (partials + `estilos.scss`)
- css/ — CSS compilado (`estilos.css`)
- index.html — arquivo principal referenciando `css/estilos.css`

Observações

- Existe um backup do CSS original em `estilos.original.css`.
- O arquivo `estilos.css` agora é gerado em `css/` via SASS.
- Certifique-se de apontar o Open Server (ou servidor que você usar) para a pasta do projeto e abrir `index.html`.
