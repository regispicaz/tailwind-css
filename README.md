# Curso Tailwind CSS - Tiago Matos

## Instalação

### Consultar documentação oficial
link: https://tailwindcss.com/docs/installation

Comando para buildar o arquivo css
```bash 
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

### Arquivo de configuração
```bash
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./public/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```
