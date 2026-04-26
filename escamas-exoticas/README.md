# Escamas Exóticas - Sitio web veterinario

[![Netlify Status](https://api.netlify.com/api/v1/badges/tu-id-de-proyecto/deploy-status)](https://app.netlify.com/sites/tu-sitio/deploys)

Sitio web profesional para la clínica veterinaria **Escamas Exóticas**, especializada en mascotas exóticas y convencionales. Incluye catálogo dinámico de animales exóticos, mapa de ubicación, agenda de citas y contacto por WhatsApp.

## Características

- **Diseño responsive** (mobile-first) con paleta de verdes y tonos tierra.
- **Catálogo de animales exóticos** cargado desde JSON, editable sin necesidad de código.
- **Filtros por categoría**: reptiles, aves, mamíferos exóticos.
- **Formulario de citas** integrado con Netlify Forms (sin backend).
- **Botón de WhatsApp** para contacto rápido y para cada animal del catálogo.
- **Mapa interactivo** de Google Maps.
- **SEO básico**: metaetiquetas, Open Graph, estructura semántica.
- **Rendimiento optimizado**: imágenes con lazy loading, CSS eficiente.

## Estructura del proyecto

escamas-exoticas/
│
├── .gitignore
├── README.md
├── index.html
├── catalogo.html
│
├── css/
│   └── styles.css
│
├── js/
│   ├── main.js
│   └── catalogo.js
│
├── data/
│   └── animales.json
│
├── img/
│   └── (aquí van las imágenes de la clínica, equipo, animales, etc.)
│
└── assets/
    └── (opcional: iconos, fuentes locales)

## Requisitos previos

- Navegador web moderno.
- Opcional: editor de código (VS Code) y Git.

## Instalación y uso local

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/escamas-exoticas.git
   cd escamas-exoticas