# Análisis Interactivo con IA: Dominion vs. Esri

Panel interactivo de análisis estratégico que compara las empresas Dominion y Esri, con capacidades de generación de contenido mediante inteligencia artificial.

## Descripción

Este proyecto es una aplicación web de una sola página (SPA) que presenta un análisis estratégico comparativo entre:

- **Dominion Global**: Integrador vertical que ofrece soluciones "llave en mano" combinando infraestructura física y digital.
- **Esri**: Plataforma geoespacial horizontal que provee el ecosistema de software ArcGIS.

### Características

- **Resumen Ejecutivo**: Visión general de ambas empresas y la oportunidad de sinergia.
- **Comparativa Visual**: Gráficos interactivos de métricas corporativas usando Chart.js.
- **Análisis por Sector**: Exploración de roles en Ciudades Inteligentes, Salud, Gestión de Emergencias y Energía.
- **Expansión Geográfica**: Presencia en Latinoamérica y Europa.
- **Hoja de Ruta**: Plan de negocio para un nuevo emprendimiento.
- **Generación con IA**: Capacidad de generar ideas y planes de negocio con la API de Gemini.

## Tecnologías Utilizadas

- HTML5
- Tailwind CSS (CDN)
- Chart.js (CDN)
- Google Fonts (Inter)
- API de Google Gemini (para funcionalidades de IA)

## Uso

Simplemente abre el archivo `index.html` en un navegador web moderno.

## Configuración de IA

> ⚠️ **Nota Importante**: Las funcionalidades de IA no funcionan en este ejemplo porque no hay una clave de API configurada.

Para habilitar las funcionalidades de IA (generación de sinergias y planes de negocio), debes:

1. Obtener una clave de API de [Google AI Studio](https://aistudio.google.com/)
2. Editar el archivo `index.html`
3. Buscar la línea que contiene `const apiKey = "";`
4. Reemplazarla con tu clave: `const apiKey = "TU_CLAVE_API_AQUI";`

**Funcionalidades que requieren la API de Gemini:**
- Botón "✨ Generar Nuevas Sinergias con IA" en la sección de Sectores
- Botón "✨ Elaborar Borrador de Plan de Negocio con IA" en la sección de Oportunidad

## Licencia

Este es un proyecto de visualización interactiva y no representa una publicación oficial de ninguna de las empresas mencionadas.

---

© 2025 Análisis Estratégico
