---
title: IChartSeriesGroup
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa un grupo de series.
type: docs
weight: 1950
url: /es/aspose.slides.charts/ichartseriesgroup/
---
## Interfaz IChartSeriesGroup

Representa un grupo de series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Permite obtener la interfaz base IChartComponent. Solo lectura [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura/escritura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). Lectura/escritura Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 por ciento del tamaño del área de trazado). Lectura/escritura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtiene o establece el ángulo de la primera porción del gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Devuelve o establece la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escritura UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Especifica el espacio entre grupos de barras o columnas, como porcentaje del ancho de la barra o columna. Lectura/escritura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Verdadero si el gráfico tiene líneas de series. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escritura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Especifica el formato HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtiene el elemento en el índice especificado. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Especifica cuánto se solapan las barras y columnas en gráficos 2-D, como porcentaje (de -100% a 100%). - -100%: Espaciado máximo (las barras están completamente separadas). - 0%: Las barras se colocan una al lado de la otra sin solapamiento ni espacio. - 100%: Solapamiento máximo (las barras se solapan completamente). Esta propiedad es lectura/escritura SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Lectura/escritura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | La información de partición personalizada para un gráfico de pastel-de-pastel o barra-de-pastel con una partición personalizada. Contiene los puntos de datos que se dibujarán en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Solo lectura [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Especifica un valor que se usará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Se usa junto con la propiedad PieSplitBy. Lectura/escritura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indica si las series de este grupo se trazan en el eje secundario. Solo lectura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Lectura/escritura UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Devuelve una colección de solo lectura de series de gráfico. Solo lectura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Devuelve el tipo de este grupo de series. Solo lectura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Proporciona acceso a barras arriba/abajo de gráficos de línea o de acciones. Solo lectura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Comentarios

1) Consulte el resumen y los comentarios de la clase ChartSeriesGroupCollection y del enum CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de series que son comunes a cada serie del grupo ("propiedades del grupo de series"). "Propiedades del grupo de series" en la clase ChartSeriesGroup es lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Ver también

* interfaz [IChartComponent](../ichartcomponent)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->