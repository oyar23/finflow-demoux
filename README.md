# FinFlow Analytics | Smart Financial Tracking & Goal Management

> **Status:** 🚧 Backend Integration & React Architecture in Progress
> **Live UX/UI Demo:** [https://finflow-demoux.vercel.app/]

## ⚠️ Current State & Demo Context
**Please Note:** The live link above demonstrates the **High-Fidelity UX/UI Prototype**.
Currently, I am migrating these static interface designs into a modular **React.js** component architecture and integrating the **Python/Airflow** backend logic described below. The demo focuses on showcasing the user experience, visual hierarchy, and interaction design.

---

## 📋 Project Overview
**FinFlow Analytics** es una plataforma integral diseñada específicamente para el contexto económico argentino. Permite a los usuarios unificar el seguimiento de sus ahorros, inversiones (CEDEARs, LECAPs, Acciones) y metas financieras a largo plazo (ej: Viajes, Vivienda).

A diferencia de un tracker convencional, FinFlow integra **pipelines de datos** para actualizar cotizaciones en tiempo real y proyectar el cumplimiento de objetivos frente a variables macroeconómicas como la inflación y la devaluación.

## 🚀 Tech Stack & Architecture

El proyecto se está construyendo sobre una arquitectura híbrida con fuerte énfasis en la ingeniería de datos y la escalabilidad del producto:

### Frontend (In Active Dev)
- **UX/UI Design:** Prototipado de alta fidelidad, diseño de interfaces reactivas y modo oscuro (Dark Mode).
- **React.js:** Migración actual de maquetas a componentes funcionales (Hooks, Context API).
- **Data Viz:** Visualización de progreso y distribución de carteras mediante gráficos dinámicos.

### Backend & Data Engineering (The Core)
- **Python:** Lenguaje principal para la lógica de negocio y procesamiento de datos financieros.
- **Apache Airflow:** Orquestación de pipelines ETL (Extract, Transform, Load).
  - *Script diario:* Extracción automatizada de cotizaciones de APIs financieras y scraping de fuentes oficiales.
  - *Normalización:* Limpieza de datos y cálculo de variaciones diarias.
- **PostgreSQL:** Diseño de base de datos relacional para usuarios, transacciones y activos históricos.

## 🛠️ Key Features (Roadmap)

- [x] **UX/UI System:** Diseño completo de Landing, Login y Dashboard (Mobile/Desktop).
- [ ] **React Migration:** Refactorización de vistas estáticas a componentes SPA.
- [x] **Data Pipeline Logic:** Scripts de Python para obtención de datos de mercado (Airflow).
- [ ] **AI Integration (Next Step):** Implementación de modelos predictivos para estimar fechas de cumplimiento de metas basándose en el rendimiento histórico del portafolio.

## 🎨 UX/UI Design Philosophy
El diseño prioriza la claridad financiera. Se utiliza una paleta de colores azul/sobria que reduce la ansiedad cognitiva asociada a las finanzas, con tarjetas de información claras ("Cards") para segmentar objetivos a corto, mediano y largo plazo, facilitando la toma de decisiones.

---
*Desarrollado por lautaro Oyarzun*
*Focus: Full Stack Development, UX/UI & Data Engineering*
=======
# finflow-demoux
Demo UX/UI
>>>>>>> fd9b092aa04c7723b66b04edd93737f14763c633
