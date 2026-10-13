# Gerador de Header de E-mail

Editor para criar headers de 1200 × 500 px com fundos e máscaras originais fornecidos pelo usuário.

## Rodar localmente

```bash
npm install
npm run dev
```

## Publicar na Vercel

Importe este diretório como um projeto Vite no painel Vercel ou conecte seu repositório Git. Build command: `npm run build`. Output directory: `dist`.

## Recursos

- 4 fundos em `public/assets/`
- Duas máscaras originais com contornos e efeitos de brilho, que espelham a posição da imagem
- Foto com recorte na máscara, upload e remoção
- Título e descrição com fonte Raleway e controles de tamanho (mínimos de 10px e 6px)
- Exportação de PNG 1200 × 500 sem elementos da interface

**Observação:** os dois arquivos de máscara enviados contêm o recorte orgânico e efeitos vermelhos; não foi encontrado um arquivo de logotipo independente. O aplicativo preserva os elementos existentes da máscara e não adiciona uma marca externa inexistente.
