---
title: IChartSeriesGroup
second_title: Aspose.Sildes para .NET API Referencia
description: Representa un grupo de series.
type: docs
weight: 1870
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Permite obtener la interfaz base IChartComponent. Solo lectura [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica cómo se representan los valores del tamaño de burbuja en el gráfico de burbujas. Lectura/escritura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Especifica el factor de escala para el gráfico de burbujas (puede estar entre el 0 y el 300 por ciento del tamaño predeterminado). Lectura/escritura Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre el 10 y el 90 por ciento del tamaño del área de trazado). Lectura/escritura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtiene o establece el ángulo de la primera porción de gráfico circular o de dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escritura UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Lectura/escritura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Verdadero si el gráfico tiene líneas de serie. Se aplica a gráficos de barras apiladas y de tipo "Of Pie". Lectura/escritura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Especifica el formato de HiLowLines. HiLowLines se aplica con los tipos de gráficos HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtiene el elemento en el índice especificado. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Especifica cuánto deben superponerse las barras y columnas en gráficos 2D, como un porcentaje (de -100% a 100%). - -100%: Espaciado máximo (las barras están completamente separadas). - 0%: Las barras están colocadas una al lado de la otra sin superposición ni espaciado. - 100%: Superposición máxima (las barras se superponen completamente). Esta propiedad es lectura/escritura SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Especifica cómo determinar qué puntos de datos están en la segunda porción o barra en un gráfico de "pie-of-pie" o de "bar-of-pie". Lectura/escritura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | La información personalizada de división para un gráfico de "pie-of-pie" o de "bar-of-pie" con una división personalizada. Contiene puntos de datos que se deben dibujar en la segunda porción o barra en un gráfico de "pie-of-pie" o de "bar-of-pie". Solo lectura [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Especifica un valor que se utilizará para determinar qué puntos de datos están en la segunda porción o barra en un gráfico de "pie-of-pie" o de "bar-of-pie". Se utiliza junto con la propiedad PieSplitBy. Lectura/escritura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indica si la serie de este grupo se traza en el eje secundario. Solo lectura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Especifica el tamaño de la segunda porción o barra de un gráfico de "pie-of-pie" o de "bar-of-pie", como un porcentaje del tamaño de la primera porción (puede estar entre el 5 y el 200 por ciento). Lectura/escritura UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Devuelve una colección de series de gráfico de solo lectura. Solo lectura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Devuelve un tipo de este grupo de series. Solo lectura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Proporciona acceso a las barras de subida/bajada de gráficos de líneas o de acciones. Solo lectura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observaciones

1) Vea el resumen y las observaciones para la clase ChartSeriesGroupCollection y el enumerado CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de serie que son comunes para cada serie en el grupo ("propiedades del grupo de series"). "Propiedades del grupo de series" en la clase ChartSeriesGroup son lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Véase también

* interfaz [IChartComponent](../ichartcomponent)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->