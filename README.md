# irpf-ca-br

Sistema criado com objetivo de facilitar a declaração do imposto de renda para quem mora no Canada

## Estrutura do Projeto

Este é um monorepo que contém:

- **Backend**: API .NET 8 localizada na pasta `backend/`
- **Frontend**: Aplicação Angular 20 SPA localizada na pasta `frontend/`

## Backend (.NET 8 API)

### Pré-requisitos
- .NET 8 SDK ou superior

### Como executar

```bash
cd backend/IrpfCaBr.Api
dotnet restore
dotnet build
dotnet run
```

A API estará disponível em `http://localhost:5000` (HTTP) e `https://localhost:5001` (HTTPS)

### Testes

```bash
cd backend/IrpfCaBr.Api
dotnet test
```

## Frontend (Angular 20 SPA)

### Pré-requisitos
- Node.js 18 ou superior
- npm 10 ou superior

### Como executar

```bash
cd frontend/irpf-ca-br-spa
npm install
npm start
```

A aplicação estará disponível em `http://localhost:4200`

### Build de produção

```bash
cd frontend/irpf-ca-br-spa
npm run build
```

### Testes

```bash
cd frontend/irpf-ca-br-spa
npm test
```

## Desenvolvimento

### Backend
O backend é uma API RESTful construída com ASP.NET Core 8, seguindo as melhores práticas de arquitetura e design.

### Frontend
O frontend é uma Single Page Application (SPA) construída com Angular 20, utilizando TypeScript e seguindo o Angular Style Guide.

## Contribuindo

1. Clone o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Crie um Pull Request
