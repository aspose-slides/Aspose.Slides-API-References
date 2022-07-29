---
title: IAxis
second_title: Referencia de la API de Aspose.Slides para .NET
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
weight: 1570
url: /es/net/aspose.slides.charts/iaxis/
---
## IAxis interface

Encapsula el objeto que representa el eje de un gráfico.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Especifica la unidad principal real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Especifica la escala de unidad principal real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Especifica el valor máximo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Especifica la unidad menor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Especifica la escala de unidad menor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Especifica el valor mínimo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Representa el tipo de agregación del eje de categoría (binning). Aplicado a la categoría. Usado con la serie Histogram o HistogramPareto solamente. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Representa si el eje de valor cruza el eje de categoría entre categorías. Esta propiedad se aplica solo a los ejes de categoría y no se aplica a los gráficos 3D. Lectura/escrituraBoolean . |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Especifica la unidad de tiempo más pequeña que se representa en el eje de fecha. Lectura/escritura[`TimeUnitType`](../timeunittype) . |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByBinWidth. Aplicado a ejes de categoría. Usado con la serie Histogram o HistogramPareto solamente. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Especifica el tipo del eje de categorías. Lectura/escritura[`CategoryAxisType`](./categoryaxistype) . |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Representa el punto del eje donde lo cruza el eje perpendicular. Lectura/escrituraSingle . |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Representa el CrossType en el eje especificado donde se cruza el otro eje. Lectura/escritura[`CrossesType`](../crossestype) . |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Especifica el valor de escala de las unidades de visualización para el eje de valor. Lectura/escritura[`DisplayUnitType`](../displayunittype) . |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Representa el formato del eje. Solo lectura[`IAxisFormat`](../iaxisformat) . |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Determina si un eje tiene un título visible. Lectura/escrituraBoolean . |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indica si se asigna automáticamente la unidad mayor del eje. Lectura/escrituraBoolean . |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indica si el valor máximo se asigna automáticamente. Lectura/escrituraBoolean . |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indica si se asigna automáticamente la unidad menor del eje. Lectura/escrituraBoolean . |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indica si el valor mínimo se asigna automáticamente. Lectura/escrituraBoolean . |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Especifica el valor del contenedor de desbordamiento automático. Si es falso: use la propiedad OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Especifica el valor de espaciado automático de etiquetas de marcas. Si es falso: use la propiedad TickLabelSpacing. Lectura/escrituraBoolean . |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Especifica el valor de espaciado automático de las marcas de graduación. Si es falso: use la propiedad TickMarksSpacing. Lectura/escrituraBoolean . |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Especifica el valor del contenedor de subdesbordamiento automático. Si es falso: use la propiedad UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura/escrituraBoolean . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indica si el formato es datos de origen vinculados. Lectura/escrituraBoolean . |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Especifica si se aplica el contenedor de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Representa si MS PowerPoint traza puntos de datos del último al primero. Lectura/escrituraBoolean . |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Especifica si se aplica el contenedor de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subdesbordamiento. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Representa si el eje es visible. Lectura/escrituraBoolean . |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Especifica la distancia de las etiquetas desde el eje. Aplicado a categoría o eje de fecha. El valor debe estar entre 0% y 1000%. Lectura/escrituraUInt16 . |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Representa la base logarítmica. El valor predeterminado es 10. Lectura/escrituraDouble . |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Representa el formato principal de las líneas de cuadrícula en un eje del gráfico. Solo lectura[`IChartLinesFormat`](../ichartlinesformat) . |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Representa el tipo de marca principal para el eje especificado. Lectura/escritura[`TickMarkType`](../tickmarktype) . |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Representa las unidades principales para el eje de fecha o valor. Lectura/escrituraDouble . |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Representa la escala de unidad mayor para el eje de fecha. Lectura/escritura[`TimeUnitType`](../timeunittype) . |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Representa el valor máximo en el eje de valores. Lectura/escrituraDouble . |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Representa el formato de líneas de cuadrícula menores en un eje de gráfico. Solo lectura[`IChartLinesFormat`](../ichartlinesformat) . |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Representa el tipo de marca de graduación menor para el eje especificado. Lectura/escritura[`TickMarkType`](../tickmarktype) . |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Representa las unidades menores para el eje de fecha o valor. Lectura/escrituraDouble . |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Representa la escala de unidad mayor para el eje de fecha. Lectura/escritura[`TimeUnitType`](../timeunittype) . |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Representa el valor mínimo en el eje de valores. Lectura/escrituraDouble . |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Representa la cadena de formato para las etiquetas de eje. Lectura/escrituraString . |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Especifica el número de contenedores cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByNumberOfBins. Aplicado a ejes de categoría. Usado con la serie Histogram o HistogramPareto solamente. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Especifica el valor personalizado del contenedor de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin se establece en falso y la propiedad IsOverflowBin es igual a verdadero. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Representa la posición del eje. Lectura/escritura[`AxisPositionType`](../axispositiontype) . |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Representa si se muestran las principales líneas de cuadrícula. Solo lecturaBoolean . |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Representa si se mostraron las líneas de cuadrícula menores. Solo lecturaBoolean . |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Representa la posición de las etiquetas de marcas en el eje especificado. Lectura/escritura[`TickLabelPositionType`](../ticklabelpositiontype) . |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Representa el ángulo de rotación de las etiquetas de marca Lectura/escrituraSingle . |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Especifica cuántas etiquetas de marca se saltan entre las etiquetas que se dibujan. Lectura/escrituraUInt32 . |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Especifica cuántas marcas de verificación se omitirán antes de que se dibuje la siguiente . Aplicado al eje de categoría o serie. Lectura/escrituraUInt16 . |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Obtiene el título del eje. Solo lectura[`IChartTitle`](../icharttitle) . |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Especifica el valor personalizado del contenedor de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin se establece en falso y la propiedad IsUnderflowBin es igual a verdadero. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Establece la propiedad IAxis.CategoryAxisType con un valor que se determina automáticamente en función de los datos del eje. |

### Ver también

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
