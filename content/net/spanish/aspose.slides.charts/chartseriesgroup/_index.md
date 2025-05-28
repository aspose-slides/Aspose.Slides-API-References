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
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica cómo se representan los valores del tamaño de burbuja en el gráfico de burbuja. Lectura/escritura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Especifica el factor de escala para el gráfico de burbuja (puede estar entre el 0 y el 300 por ciento del tamaño predeterminado). Lectura/escritura Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Devuelve el gráfico padre. Solo lectura [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Especifica el tamaño del orificio en un gráfico de dona (puede estar entre el 0 y el 90 por ciento del tamaño del área de trazado). Lectura/escritura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtiene o establece el ángulo de la primera rebanada de un gráfico circular o de dona, en grados (en dirección de las agujas del reloj desde arriba, de 0 a 360 grados). Lectura/escritura UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escritura UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Lectura/escritura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y de Porción de Pastel. Lectura/escritura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Especifica el formato de HiLowLines. HiLowLines se aplica con los tipos de gráficos HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtiene el elemento en el índice especificado. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Especifica cuánto deben superponerse las barras y columnas en gráficos 2D, como un porcentaje (de -100% a 100%). - -100%: Espaciado máximo (las barras están completamente separadas). - 0%: Las barras están colocadas una al lado de la otra sin superposición ni espaciado. - 100%: Superposición máxima (las barras se superponen completamente). Esta propiedad es de lectura/escritura SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Especifica cómo determinar qué puntos de datos están en la segunda porción o barra en un gráfico de porciones de pastel o barra de pastel. Lectura/escritura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | La información de división personalizada para un gráfico de porciones de pastel o barra de pastel con una división personalizada. Contiene puntos de datos que se dibujarán en la segunda porción o barra en un gráfico de porciones de pastel o barra de pastel. Solo lectura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Especifica un valor que se utilizará para determinar qué puntos de datos están en la segunda porción o barra en un gráfico de porciones de pastel o barra de pastel. Se utiliza junto con la propiedad PieSplitBy. Lectura/escritura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica si las series de este grupo se trazan en el eje secundario. Solo lectura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Especifica el tamaño de la segunda porción o barra de un gráfico de porciones de pastel o un gráfico de barras de pastel, como un porcentaje del tamaño de la primera porción (puede estar entre 5 y 200 por ciento). Lectura/escritura UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Devuelve una colección de series. Solo lectura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Devuelve un tipo de este grupo de series. Solo lectura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Proporciona acceso a las barras ascendentes/descendentes de un gráfico de líneas o acciones. Solo lectura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observaciones

1) Consulte el resumen y las observaciones para la clase ChartSeriesGroupCollection y la enumeración CombinableSeriesTypesGroup. 2) Un grupo de series contiene algunas propiedades de serie que son comunes para cada serie en el grupo ("propiedades de grupo de series"). Las "propiedades de grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades de grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Véase también

* interfaz [IChartSeriesGroup](../ichartseriesgroup)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->