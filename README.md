# Base limpa de API em Node

Este repositório serve exclusivamente para oferecer uma base rápida para criação de APIs em Node.

Ele possui apenas a configuração básica do Express com Typescript e o primeiro router.

## Instalação
Você pode clonar o repositório e rodar:
```bash
npm install
```

Depois clonar o arquivo `.env.example` para `.env.local`:
```bash
cp .env.example .env.local
```
E alterar as variáveis de ambiente.

## Uso
Para rodar o projeto, utilize o comando padrão:
```bash
npm run dev
```

## Adicionais
Caso queira, é interessante remover o `origin` do repositório, para adicionar seu próprio repositório remoto e continuar o desenvolvimento.

Para ver os repositórios remotos:
```bash
git remote -v
```

Para trocar o origin:
```bash
git remote remove origin
git remote add origin <url>
```
Sendo `<url>` o diretório do seu repositório remoto.