# LAR Dashboard — Promociones y Condiciones

Panel diario multifamily de **LAR Group** con datos reales de ocupación, pipeline comercial, contratos firmados y forecast de ingresos a 120 días.

## Contenido

- **`index.html`** — Dashboard self-contained (HTML + CSS + JS + Chart.js vía CDN). Se abre directamente en el navegador o se publica con GitHub Pages.

## Vista general

El dashboard consolida el snapshot del **3-mayo-2026** sobre 12 propiedades del portafolio (3.205 deptos, 4.057 reservas históricas, 2.861 contratos):

- **Ocupación del portafolio** con semáforos vs. meta (placeholder en 95% hasta cargar presupuesto real por edificio).
- **Pipeline comercial**: reservas activas, tasa de avance y fuga últimos 30 días.
- **Detalle por propiedad** con ranking por variación vs. meta.
- **Forecast de ingresos** próximos 120 días por *Fecha Declarada Ingreso*.
- **Composición del portafolio**: arrendados, disponibles, no disponibles.

## Cómo verlo

1. Abrir `index.html` directamente en el navegador, o
2. Activar **GitHub Pages** en este repo (Settings → Pages → Deploy from `main` branch / root) y acceder a la URL pública.

## Próximos pasos

- Cargar metas de ocupación reales por edificio (hoy todas en 95% como placeholder).
- Conectar fuente de datos en vivo (hoy los datos están embebidos en el HTML).
- Agregar histórico mes a mes para comparar tendencias.

## Stack

HTML + CSS + JavaScript vanilla, con [Chart.js 4.5](https://www.chartjs.org/) cargado por CDN. Sin build step, sin dependencias locales.
