# NTTTEST

## Requisitos
- .NET 8 SDK
- Node.js 18+
- Angular CLI
- Azure DevOps

---

## Ejecutar Backend
cd backend
dotnet run

---

## Ejecutar Frontend
cd frontend/cliente-app
npm install
ng serve -o

---

## Funcionalidad
1. Pantalla de consulta:
   - Seleccionar tipo de documento
   - Digitar número (8-11 dígitos)
   - Buscar

2. Pantalla resumen:
   - Muestra datos mock del cliente 23445322
   - Botón volver

---

## CI/CD
El archivo azure-pipelines.yml compila:
- Backend .NET
- Frontend Angular
- Publica artifacts
