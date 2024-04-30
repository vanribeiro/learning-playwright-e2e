# React + TypeScript + [Vite](https://vitejs.dev/) + [Playwright](https://playwright.dev/)

```bash
git clone https://github.com/vanribeiro/learning-playwright-e2e.git
cd learning-playwright-e2e
npm i
```
## Rodando o projeto

Terminal 01
```bash
npm run dev
```

## Rodando testes E2E

Terminal 02

Comandos para rodar [Playwright](https://playwright.dev/)

```bash
  npx playwright test
    #Runs the end-to-end tests.

  npx playwright test --ui
    #Starts the interactive UI mode.

  npx playwright test --project=chromium
    #Runs the tests only on Desktop Chrome.

  npx playwright test example
    #Runs the tests in a specific file.

  npx playwright test --debug
    #Runs the tests in debug mode.

  npx playwright codegen
    #Auto generate tests with Codegen.
```