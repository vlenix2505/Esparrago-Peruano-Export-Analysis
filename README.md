# Peruvian Asparagus Export Analysis: Insights into the Spanish Market (2023)

![image](https://github.com/user-attachments/assets/7efc72b2-86c9-43c2-b5d7-b650a280f0b6)



## Project Background
En el 2023, las agroexportaciones no tradicionales del Perú incrementaron a $5.045 millones durante el primer semestre, mostrando un aumento del 1.2% en comparación con el 2022. En este contexto, el espárrago se situó en el cuarto puesto entre los productos con mayor valor exportado, alcanzando US$212 millones. La Libertad fue el principal departamento exportador (ComexPerú, 2023).

Adicionalmente, el manejo eficiente de datos se ha convertido en un desafío global. Para el 2025, se estima que las empresas generarán 125 zetabytes de información. Sin embargo, solo las organizaciones con estrategias adecuadas podrán aprovechar este crecimiento de datos (Emprendedores, 2021).

Este proyecto aborda ambas perspectivas: analizar las exportaciones de espárrago al mercado español y proporcionar información clara y procesable mediante un dashboard interactivo.

Puedes acceder al dashboard interactivo presionando [este link](https://app.powerbi.com/view?r=eyJrIjoiNDg0YTRkOTUtYTczOS00NmUzLWIwMjQtNTIyNWE0MmFkMjdiIiwidCI6IjBlMGNiMDYwLTA5YWQtNDlmNS1hMDA1LTY4YjliNDlhYTFmNiIsImMiOjR9)

---

## Data Structure
El dashboard interactivo fue diseñado en Power BI y se basa en datos desglosados de exportaciones de espárrago peruano durante el 2023 de la fuente de datos ADEX Data Trade. Los elementos claves del dataset principal **BD** incluyen:

- **Mes**: Número de los meses correspodiente al intervalo de enero a diciembre.
- **Vía de transporte**: Aérea, marítima y terrestre.
- **Unidad de medida**: Caja, unidad y frascos.
- **Región**: Se incluyen las principales zonas de producción como La Libertad.
- **Razón Social**: Se detallan las empresas con mayores ingresos, destacando a GREEN PERU S.A como líder.
- **US$ FOB**: Precio total del lote exportado (en dólares)

Asimismo, para optimizar la calidad de los reportes, se decidió crear una tabla **Calendario** para almacenar las fechas y calcular efectivamente medidas como la Variación Porcentual de ingresos entre cada mes. Como buena práctica, las **Medidas** se guardaron en un tabla con el nombre respectivo.

![image](https://github.com/user-attachments/assets/a6106dec-f689-4949-a8b6-a27852e02e56)


## Executive Summary
El análisis mostró las siguientes observaciones destacadas:

1. **Ingresos Totales**: Se registraron exportaciones por un valor total de **$72.91 millones**.
2. **Peso Bruto Total**: Se exportaron **26.19 millones de kilogramos**.
3. **Transporte Predominante**: El 71.42% del transporte se realizó por vía marítima, mientras que el 28.52% fue aéreo y solo el 0.06% terrestre.
4. **Unidades de Medida**: El 62.16% de las exportaciones fueron en cajas, el 19.37% en unidades y el 8.81% en frascos.
5. **Tendencias Mensuales**: Diciembre destacó como el mes con mayores ingresos ($8.8 millones), mientras que febrero registró la mayor caída (-40.17%) respecto al mes previo.
6. **Empresas Líderes**: GREEN PERU S.A lideró las exportaciones con ingresos de **$18.13 millones**.
7. **Región Principal**: La Libertad generó el 73.09% del valor total exportado, consolidándose como el principal origen de las exportaciones.

---

## Conclusion
Este análisis demuestra el papel clave del espárrago como producto de exportación en el mercado español y la relevancia de La Libertad como motor de estas exportaciones. El uso del dashboard permite identificar rápidamente tendencias, oportunidades de mejora y rendimiento de empresas destacadas.

El informe sirve como herramienta estratégica para empresas del sector agroexportador y autoridades gubernamentales, facilitando la toma de decisiones basadas en datos.


