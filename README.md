# servless-nodejs-otimizar-imagem
Serviço servless para otimização de tamanho de imagem na amazon utilizando Framework Serverless

- **Tutorial:** https://www.youtube.com/watch?v=jiP45rEOEbA
- **Github:** https://github.com/rocketseat-content/youtube-serverless-node-aws-lambda

## Comandos
Para executar deploy na AWS usando Serverless Framework:

```serverless deploy -v```

Para executar deploy utilizando comandos configurados no package.json do NodeJS:

```npm run deploy```

Para executar uma função Lambda:

```serverless invoke -f optimize -l```

Para remover stack da AWS:

```serverless remove```