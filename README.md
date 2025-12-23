# Hotel Bookings – Data Storytelling with Power BI

Este repositorio contiene un informe interactivo desarrollado en **Power BI** que analiza las **cancelaciones de reservas hoteleras** mediante técnicas de **visualización narrativa (data storytelling)**.

El proyecto se basa en el conjunto de datos *Hotel Bookings* (2015–2017) y ha sido realizado como parte de una práctica académica centrada en analítica visual y narrativa de datos.

---

## Requisitos previos

### Instalación de Power BI Desktop

Para poder abrir y explorar el informe es **necesario instalar Power BI Desktop**.

- Descarga gratuita desde la web oficial de Microsoft:  
  👉 https://powerbi.microsoft.com/desktop/
- Disponible para sistemas **Windows**
- No se requiere licencia de pago para visualizar el informe

Una vez instalado, abre el archivo del informe (`.pbix`) directamente con Power BI Desktop.

---

## Contenido del repositorio

- `PEC3-StoryTelling.pbix` → Informe interactivo en Power BI  
- `hotel_bookings.csv` → Conjunto de datos original  
- `README.md` → Descripción del proyecto y guía de uso  

---

## Descripción del informe

El informe analiza más de **80.000 reservas hoteleras** realizadas en dos hoteles (un hotel urbano y un resort) entre los años **2015 y 2017**.

El objetivo principal es **entender por qué se producen las cancelaciones** y qué factores influyen más en el riesgo de que una reserva sea cancelada.

El análisis se presenta siguiendo un enfoque de **storytelling con datos**, donde cada página del informe responde a una pregunta concreta y conduce progresivamente a una conclusión final.

---

## Estructura del informe

El dashboard está organizado en varias páginas narrativas:

### 1️ - El problema de las cancelaciones
- Visión general del dataset
- Tasa global de cancelación
- Contextualización del impacto del fenómeno

**Pregunta clave:**  
> ¿Son realmente relevantes las cancelaciones?

---

### 2️ - Diferencias entre tipos de hotel
- Comparación entre *City Hotel* y *Resort Hotel*
- Identificación de diferencias estructurales en las tasas de cancelación

**Pregunta clave:**  
> ¿El tipo de hotel influye en el riesgo de cancelación?

---

### 3️ - Antelación de la reserva (Lead Time)
- Relación entre la antelación de la reserva y la probabilidad de cancelación
- Análisis conjunto de riesgo y volumen de reservas

**Pregunta clave:**  
> ¿Reservar con mucha antelación aumenta el riesgo de cancelación?

---

### 4️ - Condiciones de la reserva: tipo de depósito
- Comparación entre reservas sin depósito, reembolsables y no reembolsables
- Análisis crítico de resultados contraintuitivos

**Pregunta clave:**  
> ¿El depósito reduce realmente las cancelaciones o refleja un mayor riesgo?

---

### 5️ - Perfil del cliente (enfoque humano)
- Análisis por tipo de cliente (*Transient, Contract, Group, Transient-Party*)
- Filtros interactivos por hotel, país y antelación
- Cierre narrativo centrado en el comportamiento humano

**Pregunta clave:**  
> ¿Quién cancela más y por qué?

---

## Interactividad

El informe permite:
- Filtrar por **tipo de hotel**
- Filtrar por **país de origen**
- Filtrar por **rango de antelación**
- Explorar cómo cambian los patrones de cancelación según el contexto

Esto refuerza la idea de que el riesgo de cancelación **no depende de un único factor**, sino de la combinación de condiciones y perfil del cliente.

---

## Conclusión

Este proyecto demuestra cómo la visualización de datos, combinada con una narrativa clara, permite transformar datos complejos en **insights comprensibles y accionables**.

El análisis pone el foco no solo en los números, sino en **las decisiones humanas detrás de las cancelaciones**, ofreciendo una visión útil tanto desde el punto de vista analítico como de gestión hotelera.

---

## Autor

Proyecto desarrollado con fines académicos como ejercicio de **data storytelling y visual analytics**.
