# Playwright - Guia de Uso e Funcionalidades

Este documento contém um resumo das funcionalidades e conceitos abordados nas aulas sobre Playwright.

O Playwright é uma ferramenta poderosa para automação de navegadores, oferecendo suporte tanto para execução de testes em linha de comando (CLI) quanto com interface gráfica (GUI). A execução via CLI é ideal para integrar testes em pipelines de CI/CD, proporcionando rapidez e flexibilidade, com comandos para executar todos os testes, testes específicos ou em navegadores específicos, usando flags como --headless ou --headed. Já a GUI, acessada pelo comando npx playwright show-report, facilita a visualização de resultados, logs detalhados e reexecução de testes, sendo especialmente útil para depuração e análise. Além disso, o Trace Viewer permite uma análise visual detalhada das interações do navegador, ajudando a identificar e corrigir problemas de forma eficiente. Essas funcionalidades tornam o Playwright uma solução robusta para testes modernos.

---

## 1. Playwright Installation

### Descrição:
O Playwright é uma biblioteca moderna para automação de navegadores que suporta os navegadores principais como Chromium, Firefox e WebKit. O objetivo desta etapa foi instalar e configurar o Playwright em um ambiente de desenvolvimento.

### Passos para instalação:
1. Certifique-se de ter o Node.js instalado.
2. Execute o seguinte comando para instalar o Playwright:
   ```bash
   npm init playwright@latest


