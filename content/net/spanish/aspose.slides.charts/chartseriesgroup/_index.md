---
title: ChartSeriesGroup
second_title: Aspose.Sildes para .NET Referencia de API
description: Representa un grupo de series.
type: docs
weight: 1470
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
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtiene o establece el ángulo de la primera porción de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Obtiene o establece la distancia entre series de datos en un gráfico 3D, como un porcentaje del ancho del marcador. El valor debe estar entre 0 y 500. Lectura/escritura UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Obtiene o establece el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. El valor debe estar entre 0 y 500. Lectura/escritura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escritura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Especifica el formato HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtiene el elemento en el índice especificado. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Especifica cuánto deben superponerse las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). - -100%: Espaciado máximo (las barras están completamente separadas). - 0%: Las barras se colocan una al lado de la otra sin superposición ni espaciado. - 100%: Superposición máxima (las barras se superponen completamente). Esta propiedad es lectura/escritura SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Lectura/escritura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | La información de división personalizada para un gráfico de pastel-de-pastel o barra-de-pastel con una división personalizada. Contiene puntos de datos que se dibujarán en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Solo lectura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Se usa junto con la propiedad PieSplitBy. Lectura/escritura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica si la serie de este grupo se dibuja en el eje secundario. Solo lectura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Lectura/escritura UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Devuelve una colección de series. Solo lectura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Devuelve un tipo de este grupo de series. Solo lectura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Proporciona acceso a las barras up/down de un gráfico de línea o de acciones. Solo lectura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observaciones

1) Consulte el resumen y las observaciones para la clase ChartSeriesGroupCollection y el enum CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de series que son comunes para cada serie del grupo ("propiedades del grupo de series"). "Propiedades del grupo de series" en la clase ChartSeriesGroup es lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección solo lectura en la clase ChartSeries.

### Véase también

* interfaz [IChartSeriesGroup](../ichartseriesgroup)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->