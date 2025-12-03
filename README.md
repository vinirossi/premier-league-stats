# 🏆 Premier League Stats

**Premier League Stats** é um projeto de estudo desenvolvido em **Angular 20**, que consome dados da **Football API** para exibir a tabela de classificação e os próximos jogos da Premier League. O objetivo é praticar consumo de API, organização de arquitetura front-end e criação de interfaces responsivas.

---

## 📌 Visão Geral

Este projeto tem como foco:

- Exibir a **tabela de classificação** da Premier League  
- Mostrar os **próximos jogos** da competição  
- Trabalhar com **Angular 20**, **HttpClient**, **Signals / RxJS**  
- Criar um dashboard moderno, rápido e acessível  
- Servir como projeto de estudo e portfólio para LinkedIn e GitHub

---

## 🧰 Tecnologias Utilizadas

- **Angular 20**
- **TypeScript**
- **RxJS** ou **Angular Signals** (a definir)
- **Angular Router**
- **HttpClient**
- **Tailwind CSS** ou **Angular Material** (a definir)
- **Football API**
- **Jest** (opcional)
- **GitHub Actions** (opcional)

---

## 📊 Funcionalidades (Planejadas)

- ✔️ Página de **Tabela de Classificação**
- ✔️ Página de **Próximos Jogos**
- 🔜 Página **Detalhes do Time**
- 🔜 Busca por time
- 🔜 Filtros por rodada/data
- 🔜 Tema claro/escuro
- 🔜 Exportar dados (CSV)

---

## 📁 Estrutura Sugerida do Projeto
    src/
    ├── app/
    │ ├── core/
    │ │ ├── services/
    │ │ └── models/
    │ ├── features/
    │ │ ├── standings/
    │ │ ├── fixtures/
    │ │ └── team/
    │ ├── shared/
    │ ├── app-routing.module.ts
    │ └── app.component.ts
    └── environments/
    ├── environment.ts
    └── environment.prod.ts
