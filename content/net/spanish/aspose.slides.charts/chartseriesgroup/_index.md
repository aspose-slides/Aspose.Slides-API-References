---
title: ChartSeriesGroup
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un grupo de series.
type: docs
weight: 1380
url: /es/aspose.slides.charts/chartseriesgroup/
---

## Clase ChartSeriesGroup

Representa un grupo de series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica cómo se representan los valores del tamaño de burbujas en el gráfico de burbujas. Lectura/escritura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño por defecto). Lectura/escritura Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Devuelve el gráfico padre. Solo lectura [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre 0 y 90 por ciento del tamaño del área de trazado). Lectura/escritura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtiene o establece el ángulo de la primera porción de un gráfico circular o de dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escritura UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Lectura/escritura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Verdadero si el gráfico tiene líneas de serie. Se aplica a gráficos de barras apiladas y OfPie. Lectura/escritura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Especifica el formato de HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtiene el elemento en el índice especificado. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Especifica cuánto se superpondrán las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). - -100%: Espaciado máximo (las barras están completamente separadas). - 0%: Las barras están colocadas una al lado de la otra sin superposición ni espaciado. - 100%: Superposición máxima (las barras se superponen completamente). Esta propiedad es lectura/escritura SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Especifica cómo determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pie de pie o barra de pie. Lectura/escritura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | La información de división personalizada para un gráfico de pie de pie o barra de pie con una división personalizada. Contiene puntos de datos que se dibujarán en la segunda porción o barra en un gráfico de pie de pie o barra de pie. Solo lectura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Especifica un valor que se utilizará para determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pie de pie o barra de pie. Se utiliza junto con la propiedad PieSplitBy. Lectura/escritura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica si la serie de este grupo se traza en el eje secundario. Solo lectura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Especifica el tamaño de la segunda porción o barra de un gráfico de pie de pie o un gráfico de barra de pie, como un porcentaje del tamaño de la primera porción (puede estar entre 5 y 200 por ciento). Lectura/escritura UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Devuelve una colección de series. Solo lectura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Devuelve un tipo de este grupo de series. Solo lectura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Provee acceso a las barras de subida/bajada de gráficos de línea o de acciones. Solo lectura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observaciones

1) Consulte el resumen y las observaciones para la clase ChartSeriesGroupCollection y el enumerado CombinableSeriesTypesGroup. 2) Un grupo de series contiene algunas propiedades de serie comunes para cada serie en el grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Véase también

* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../) 

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->