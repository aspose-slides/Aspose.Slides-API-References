---
title: IChartSeriesGroup
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa grupo de series.
type: docs
weight: 1810
url: /es/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Representa grupo de series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Permite obtener la interfaz base de IChartComponent. Solo lectura[`IChartComponent`](../ichartcomponent) . |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura/escritura[`BubbleSizeRepresentationType`](../bubblesizerepresentationtype) . |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Especifica el factor de escala para el gráfico de burbujas (puede ser entre 0 y 300 por ciento del tamaño predeterminado). Lectura/escrituraInt32 . |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Especifica el tamaño del agujero en un gráfico de anillos (puede estar entre el 10 y el 90 por ciento del tamaño del área de trazado). Lectura/escrituraByte . |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtiene o establece el ángulo de la primera porción del gráfico circular o de anillos, en grados (en el sentido de las agujas del reloj desde arriba, de 0 a 360 grados). Lectura/escrituraUInt16 . |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Devuelve o establece la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escrituraUInt16 . |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Especifica el espacio entre los grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Lectura/escrituraUInt16 . |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escrituraBoolean . |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Especifica el formato HiLowLines. HiLowLines aplicado con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de datos de la serie tiene un color diferente. Lectura/escrituraBoolean . |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtiene el elemento en el índice especificado. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Especifica cuánto se superpondrán las barras y las columnas en los gráficos 2D (de -100 a 100). Lectura/escrituraSByte . |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Especifica cómo determinar qué puntos de datos se encuentran en el segundo gráfico circular o de barra en un gráfico circular o de barra circular. Lectura/escritura[`PieSplitType`](../piesplittype) . |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | La información de división personalizada para un gráfico circular o de barra circular con una división personalizada. -gráfico circular. Solo lectura[`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection) . |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Especifica un valor que se utilizará para determinar qué puntos de datos se encuentran en el segundo gráfico circular o de barra en un gráfico circular o de barra circular. Se usa junto con la propiedad PieSplitBy. Lectura/escrituraDouble . |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indica si la serie de este grupo está graficada en el eje secundario. Solo lecturaBoolean . |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Especifica el tamaño de la segunda tarta o barra de un gráfico de tarta o un gráfico de barra de tarta, como un porcentaje del tamaño de la primera tarta (puede estar entre 5 y 200 por ciento). Leer escribirUInt16 . |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Devuelve una colección de series de gráficos de solo lectura. Solo lectura[`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection) . |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Devuelve un tipo de este grupo de series. Solo lectura[`CombinableSeriesTypesGroup`](../combinableseriestypesgroup) . |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Proporcionó acceso a las barras arriba/abajo del gráfico de línea o cotizaciones. Solo lectura[`IUpDownBarsManager`](../iupdownbarsmanager) . |

### Observaciones

1) Ver resumen y comentarios para la clase ChartSeriesGroupCollection y la enumeración CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de serie que son comunes para cada serie en grupo ("propiedades de grupo de serie"). "Propiedades de grupo de serie" en la clase ChartSeriesGroup es lectura/escritura. Cada una de las "propiedades de grupo de serie" puede tener una proyección de solo lectura en la clase ChartSeries.

### Ver también

* interface [IChartComponent](../ichartcomponent)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
