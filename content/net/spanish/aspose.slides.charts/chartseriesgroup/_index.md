---
title: ChartSeriesGroup
second_title: Aspose.Sildes para la referencia de API .NET
description: Representa un grupo de series.
type: docs
weight: 1460
url: /es/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup clase

Representa un grupo de series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura/escritura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). Lectura/escritura Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Devuelve el gráfico principal. Solo lectura [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 0 y 90 por ciento del tamaño del área de trazado). Lectura/escritura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtiene o establece el ángulo de la primera porción de un gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Devuelve o establece la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escritura UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Especifica el espacio entre los conglomerados de barras o columnas, como porcentaje del ancho de la barra o columna. Lectura/escritura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True si el gráfico tiene líneas de series. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escritura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Especifica el formato HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtiene el elemento en el índice especificado. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Especifica cuánto se solapan las barras y columnas en los gráficos 2-D, como porcentaje (de -100 % a 100 %). - -100 %: Espaciado máximo (las barras están completamente separadas). - 0 %: Las barras se colocan una al lado de la otra sin solapamiento ni espacio. - 100 %: Solapamiento máximo (las barras se solapan completamente). Esta propiedad es lectura/escritura SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. Lectura/escritura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | La información de división personalizada para un gráfico pie-of-pie o bar-of-pie con una división personalizada. Contiene los puntos de datos que se deben dibujar en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. Solo lectura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Especifica un valor que se usará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. Se usa junto con la propiedad PieSplitBy. Lectura/escritura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica si las series de este grupo se trazan en el eje secundario. Solo lectura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Especifica el tamaño del segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie, como porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Lectura/escritura UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Devuelve una colección de series. Solo lectura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Devuelve un tipo de este grupo de series. Solo lectura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Proporciona acceso a las barras up/down de un gráfico de líneas o de acciones. Solo lectura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Comentarios

1) Consulte el resumen y los comentarios para la clase ChartSeriesGroupCollection y la enumeración CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de series que son comunes para cada serie en el grupo ("propiedades del grupo de series"). "Propiedades del grupo de series" en la clase ChartSeriesGroup es lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección solo lectura en la clase ChartSeries.

### Ver también

* interfaz [IChartSeriesGroup](../ichartseriesgroup)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->