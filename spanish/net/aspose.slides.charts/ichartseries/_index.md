---
title: IChartSeries
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una serie de gráficos.
type: docs
weight: 1790
url: /es/net/aspose.slides.charts/ichartseries/
---
## IChartSeries interface

Representa una serie de gráficos.

```csharp
public interface IChartSeries : IChartComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Permite obtener la interfaz base de IChartComponent. Solo lectura[`IChartComponent`](../ichartcomponent) . |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Especifica la forma de una serie de un gráfico de barras 3D. El cambio del valor de esta propiedad puede causar que cambie automáticamente el Tipo de serie. Lectura/escritura[`ChartShapeType`](../chartshapetype) . |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Esta es la propiedad no solo de esta serie, sino de todas las series del grupo principal : esta es la proyección de la propiedad de grupo adecuada. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.BubbleSizeRepresentation para cambiar el valor. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Especifica el factor de escala para el gráfico de burbujas (puede ser entre 0 y 300 por ciento del tamaño predeterminado). Esta es la propiedad no solo de esta serie sino de todas las series de la serie principal grupo: esta es la proyección del grupo apropiado propiedad. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.BubbleSizeScale para cambiar el valor. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Devuelve la colección de puntos de datos de esta serie. Solo lectura[`IChartDataPointCollection`](../ichartdatapointcollection) . |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Especifica el tamaño del agujero en un gráfico de anillos (puede estar entre el 10 y el 90 por ciento del tamaño del área de trazado). Esta es la propiedad no solo de esta serie, sino de todas las series de la serie principal group - esta es la proyección de la propiedad de grupo apropiada. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.DoughnutHoleSize para cambiar el valor. Solo lecturaByte . |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Representa ErrorBars de serie con desviación X.  Las barras de error con dirección X están disponibles para series de tipo área, barra, dispersión y burbuja. Para cualquier otro tipo de gráfico, esta propiedad devuelve un valor nulo (incluidos los gráficos 3D). En el caso de valores personalizados, use la colección DataPoints para especificar value (con[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) propiedad).  Solo lectura[`IErrorBarsFormat`](../ierrorbarsformat) . |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Representa ErrorBars de serie con desviación Y.  ErrorBars con dirección Y están disponibles para series de tipo área, barra, línea, dispersión y burbuja. Para cualquier otro tipo de gráfico, esta propiedad devuelve un valor nulo (incluidos los gráficos 3D). En el caso de valores personalizados, use la recopilación de DataPoints para especificar value (con[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) propiedad).  Solo lectura[`IErrorBarsFormat`](../ierrorbarsformat) . |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | La distancia de un sector circular abierto desde el centro del gráfico circular se expresa como un porcentaje del diámetro circular. Lectura/escrituraInt32 . |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Especifica el ángulo de la primera porción del gráfico circular o de anillos, en grados (en el sentido de las agujas del reloj desde arriba, de 0 a 360 grados). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de la serie principal : proyección de propiedad de grupo apropiada. Entonces, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.FirstSliceAngle para cambiar el valor. Solo lecturaUInt16 . |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Devuelve el formato de una serie. Solo lectura[`IFormat`](../iformat) . |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Devuelve o establece la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Esta es la propiedad no solo de esta serie, sino de todas las series de la serie principal group: esta es la proyección del grupo apropiado propiedad. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.GapDepth para cambiar el valor. Solo lecturaInt32 . |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Especifica el espacio entre los grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Esta es la propiedad no solo de esta serie sino de todas las series del grupo principal : esta es la proyección de la propiedad de grupo adecuada. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.GapWidth para cambiar el valor. Solo lecturaInt32 . |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Determina si hay líneas de serie para esta serie y series afines. Esta es la propiedad no solo de esta serie sino de todas las series del grupo principal : esta es la proyección de la propiedad de grupo apropiada. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.HasSeriesLines para cambiar el valor. Use la propiedad ParentSeriesGroup.SeriesLinesFormat para formatear líneas de serie. Solo lecturaBoolean . |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Determina si el gráfico de líneas o cotizaciones tiene barras arriba/abajo. Esta es la propiedad no solo de esta serie, sino de todas las series del grupo principal : esta es la proyección de la propiedad de grupo adecuada. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.UpDownBars.HasUpDownBars para cambiar el valor. Use la propiedad ParentSeriesGroup.UpDownBars para dar formato a las barras arriba/abajo. Solo lecturaBoolean . |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Especifica el color sólido invertido para la serie. Para aplicar la configuración de color, configure el formato de serie FillType a FillType.Solid. Lectura/escritura[`IColorFormat`](../../aspose.slides/icolorformat) . |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Especifica que la serie de barras, columnas o burbujas invertirá sus colores si el valor es negativo. Lectura/escrituraBoolean . |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Especifica que cada marcador de datos en la serie tiene un color diferente. Esta es la propiedad no solo de esta serie, sino de todas las series del grupo principal de la serie : esta es la proyección de la propiedad de grupo adecuada. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.IsColorVaried para cambiar el valor. Solo lecturaBoolean . |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Devuelve las Etiquetas de una serie. Solo lectura[`IDataLabelCollection`](../idatalabelcollection) . |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Devolver marcador de serie. Solo lectura[`IMarker`](../imarker) . |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Devuelve el nombre de la serie. Solo lectura[`IStringChartValue`](../istringchartvalue) . |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Devuelve o establece el formato de número para tamaños de burbuja de serie. Lectura/escrituraString . |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Devuelve o establece el formato de número para valores de serie. Lectura/escrituraString . |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Devuelve o establece el formato de número para los valores de la serie x. Lectura/escrituraString . |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Devuelve o establece el formato de número para los valores de la serie y. Lectura/escrituraString . |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Devuelve el orden de una serie. Lectura/escrituraInt32 . |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Especifica cuánto se superpondrán las barras y las columnas en los gráficos 2D (de -100 a 100). Esta es la propiedad no solo de esta serie, sino de todas las series del grupo de la serie principal : esta es la proyección de la propiedad de grupo adecuada. Entonces, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.Overlap para cambiar el valor. Solo lecturaSByte . |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Representa el diseño de las etiquetas de categoría principal. Se aplica solo a los gráficos de mapa de árbol. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Devuelve el grupo de serie principal. Solo lectura[`IChartSeriesGroup`](../ichartseriesgroup) . |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Especifica cómo determinar qué puntos de datos se encuentran en el segundo gráfico circular o barra en un gráfico circular o de barra circular. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series principales - esta es la proyección de propiedad de grupo apropiada. Entonces, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.PieSplitBy para cambiar el valor. Solo lectura[`PieSplitType`](../piesplittype) . |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | La información de división personalizada para un gráfico circular o de barra circular con una división personalizada. -gráfico circular. Esta es la propiedad no solo de esta serie sino de todas las series de la serie principal grupo: esta es la proyección de la propiedad de grupo apropiada Solo lectura[`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection) . |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Especifica un valor que se utilizará para determinar qué puntos de datos se encuentran en el segundo gráfico circular o de barra en un gráfico circular o de barra circular. Se usa junto con la propiedad PieSplitBy. Esta es la propiedad no solo de esta serie sino de todas las series del grupo principal : esta es la proyección de la propiedad de grupo apropiada. Entonces, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.PieSplitPosition para cambiar el valor. Solo lecturaDouble . |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Indica si esta serie se grafica en el segundo eje de valor. Lectura/escrituraBoolean . |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Representa el método del cuartil. Se aplica solo a los gráficos BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Representa la entrada de la leyenda relacionada con esta serie Solo lectura[`ILegendEntryProperties`](../ilegendentryproperties) . |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Especifica el tamaño de la segunda tarta o barra de un gráfico de tarta o un gráfico de barra de tarta, como un porcentaje del tamaño de la primera tarta (puede estar entre 5 y 200 por ciento). Esta es la propiedad no solo de esta serie, sino de todas las series del grupo principal de la serie : esta es la proyección de la propiedad de grupo adecuada. Entonces, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de la serie principal. Use la propiedad de lectura/escritura ParentSeriesGroup.SecondPieSize para cambiar el valor. Solo lecturaUInt16 . |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Representa líneas de conexión. Se aplica solo a los gráficos de cascada. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Representa puntos interiores. True si los puntos internos se muestran en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escrituraBoolean . |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Representa marcadores medios. Verdadero si la línea media se muestra en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escrituraBoolean . |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Representa marcadores medios. Verdadero si se muestran marcadores de media en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escrituraBoolean . |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Representa puntos atípicos. True si se muestran puntos atípicos en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escrituraBoolean . |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Representa el suavizado de curvas. True si el suavizado de curvas está activado para el gráfico de líneas o el gráfico de dispersión. Se aplica solo a líneas y dispersión conectadas por gráficos de líneas. Lectura/escrituraBoolean . |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Colección de líneas de tendencia de series Solo lectura[`ITrendlineCollection`](../itrendlinecollection) . |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Devuelve un tipo de esta serie. Lectura/escritura[`ChartType`](../charttype) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Devuelve un color automático de serie basado en el índice de serie y el estilo de gráfico. Este color se usa de forma predeterminada si FillType es igual a NotDefined. |

### Ver también

* interface [IChartComponent](../ichartcomponent)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->