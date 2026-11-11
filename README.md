# Quarteirões para o LIRAa

Aplicativo web desenvolvido com React, TypeScript e Vite.

## Publicação no GitHub Pages

O projeto está configurado para o endereço `https://ricardosoares2607-bit.github.io/liraa/`.

A publicação é automática pelo GitHub Actions: ao enviar alterações para a branch `main`, o workflow `.github/workflows/deploy.yml` instala as dependências, executa `npm run build` e publica a pasta `dist`.

No repositório, acesse **Settings → Pages** e selecione **GitHub Actions** em **Build and deployment → Source**. Não selecione `Deploy from a branch` para este fluxo.

## Executar localmente

Requer Node.js 22 ou superior.

```bash
npm install
npm run dev
```
