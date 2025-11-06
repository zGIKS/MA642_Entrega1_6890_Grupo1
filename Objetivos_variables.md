# Variables extraídas de los objetivos

A continuación se presenta cada objetivo exactamente como aparece en `Objetivos.tex`, seguido por una tabla con las variables identificadas, el tipo de variable y la escala de medición propuesta.

---

## Objetivo General

Analizar las exportaciones de palta desde el Perú hacia los países de América del Norte durante el año 2025, con el fin de identificar los volúmenes exportados y las principales características logísticas, comerciales de los envíos realizados.

| Variable(s) | Tipo de variable | Escala de medición |
|---|---:|---|
| Producto (palta) | Cualitativa | Nominal |
| Origen (País) | Cualitativa | Nominal |
| Zona destino (América del Norte) | Cualitativa | Nominal |
| Periodo temporal (año) | Cuantitativa discreta / temporal | Intervalo |
| Volúmenes exportados (peso/volumen) | Cuantitativa continua | Razón |
| Características logísticas (p.ej. medio de transporte, puerto, tiempo de tránsito) | Mixta: cualitativa (medio/puerto) y cuantitativa (tiempo) | Nominal (medio/puerto), Razón (tiempo) |
| Características comerciales (p.ej. precio FOB, empresa exportadora) | Mixta: cuantitativa y cualitativa | Razón (precio), Nominal (empresa) |

---

## Objetivo Específico 1

Determinar el uso de las vías de transporte empleadas en las exportaciones de palta desde el Perú hacia los países de América del Norte durante el año 2025, identificando el medio predominante utilizado para cada país de destino.

| Variable(s) | Tipo de variable | Escala de medición |
|---|---:|---|
| Medio de transporte (marítimo/aéreo/terrestre) | Cualitativa | Nominal |
| Medio predominante por país (categoría derivada) | Cualitativa | Nominal |
| País de destino | Cualitativa | Nominal |
| Periodo (año) | Cuantitativa discreta / temporal | Intervalo |

---

## Objetivo Específico 2

Analizar la distribución del valor “Precio total del lote exportado en dólares estadounidenses” (FOB) de las exportaciones de Palta desde Perú hacia América del Norte a través del puerto de Rodman durante el año 2025.

| Variable(s) | Tipo de variable | Escala de medición |
|---|---:|---|
| Precio total del lote (FOB, USD) | Cuantitativa continua | Razón |
| Puerto de embarque (Rodman) | Cualitativa | Nominal |
| Periodo (año) | Cuantitativa discreta / temporal | Intervalo |
| Estadísticos de distribución (media, mediana, desviación, percentiles) — derivados | Cuantitativa | Razón |

---

## Objetivo Específico 3

Analizar la distribución de la cantidad de unidades exportadas por puerto de destino, identificando cuál presenta mayor estabilidad en sus envíos, cuál concentra el mayor volumen exportado y si existen patrones inusuales en los puertos de Miami y Balboa.

| Variable(s) | Tipo de variable | Escala de medición |
|---|---:|---|
| Cantidad de unidades exportadas (unidades, cajas o toneladas según fuente) | Cuantitativa discreta (si son unidades) o continua (si es peso/volumen) — se recomienda especificar unidad | Razón |
| Puerto de destino | Cualitativa | Nominal |
| Estabilidad en envíos (p.ej. desviación, coeficiente de variación) — derivada | Cuantitativa continua | Razón |
| Volumen concentrado por puerto (suma/porcentaje) — derivada | Cuantitativa continua | Razón |
| Indicador de patrón inusual (anomalía) — p.ej. etiqueta Sí/No | Cualitativa (binaria) | Nominal |

---

## Objetivo Específico 4

Evaluar el comportamiento del precio total del lote exportado en dólares estadounidenses en las exportaciones de palta desde Perú realizadas por las empresas COSCO SHIPPING LINES (PERU) S.A., IAN TAYLOR PERU S.A.C. y MEDITERRANEAN SHIPPING COMPANY DEL PERU S.A.C. durante el año 2025, a fin de comparar la variabilidad y características de los valores registrados entre dichas compañías.

| Variable(s) | Tipo de variable | Escala de medición |
|---|---:|---|
| Precio total del lote (FOB, USD) | Cuantitativa continua | Razón |
| Empresa exportadora (COSCO..., IAN TAYLOR..., MEDITERRANEAN...) | Cualitativa | Nominal |
| Rango total (precio) — derivado | Cuantitativa continua | Razón |
| Mediana del precio — derivado | Cuantitativa continua | Razón |
| Periodo (año) | Cuantitativa discreta / temporal | Intervalo |

---

## Notas y recomendaciones
- Es importante normalizar las unidades (p. ej., kilos, toneladas, cajas) y documentar la unidad usada para "cantidad de unidades".
- Se recomienda usar la moneda USD ya que el objetivo especifica FOB en dólares estadounidenses.
- Para variables temporales se sugiere definir la granularidad (mensual, semanal) según la disponibilidad de los datos. El año se coloca como escala de intervalo.
- Variables derivadas (rango, mediana, indicadores de estabilidad/anomalía) se obtienen a partir de las variables primarias.

---

Archivo generado/actualizado automáticamente a partir de `Objetivos.tex`.
