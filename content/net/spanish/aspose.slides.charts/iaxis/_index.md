---
title: IAxis
second_title: Referencia de API de Aspose.Sildes para .NET
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
weight: 1710
url: /es/aspose.slides.charts/iaxis/
---
## Interfaz IAxis

Encapsula el objeto que representa el eje de un gráfico.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Especifica la unidad mayor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Especifica la escala de la unidad mayor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Especifica el valor máximo real en el eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Especifica la unidad menor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Especifica la escala de la unidad menor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Especifica el valor mínimo real en el eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Representa el tipo de agregación del eje de categorías (agrupación). Aplicado a categorías. Se usa solo con series Histogram o HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad se aplica solo a ejes de categorías y no se aplica a gráficos 3-D. Lectura/escritura Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Especifica la unidad de tiempo más pequeña representada en el eje de fechas. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByBinWidth. Aplicado a ejes de categorías. Se usa solo con series Histogram o HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Especifica el tipo del eje de categorías. Lectura/escritura [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Representa el punto en el eje donde el eje perpendicular lo cruza. Lectura/escritura Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Representa el CrossType en el eje especificado donde cruza el otro eje. Lectura/escritura [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Especifica el valor de escala de las unidades de visualización para el eje de valores. Lectura/escritura [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Representa el formato del eje. Solo lectura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Determina si un eje tiene un título visible. Lectura/escritura Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indica si la unidad mayor del eje se asigna automáticamente. Lectura/escritura Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indica si el valor máximo se asigna automáticamente. Lectura/escritura Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indica si la unidad menor del eje se asigna automáticamente. Lectura/escritura Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indica si el valor mínimo se asigna automáticamente. Lectura/escritura Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Especifica el valor automático del contenedor de desbordamiento. Si es false: use la propiedad OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Especifica el valor automático de espaciado de etiquetas de marcas. Si es false: use la propiedad TickLabelSpacing. Lectura/escritura Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Especifica el valor automático de espaciado de marcas de graduación. Si es false: use la propiedad TickMarksSpacing. Lectura/escritura Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Especifica el valor automático del contenedor de subdesbordamiento. Si es false: use la propiedad UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura/escritura Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indica si el formato está vinculado a datos de origen. Lectura/escritura Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Especifica si se aplica el contenedor de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Representa si MS PowerPoint traza los puntos de datos de último a primero. Lectura/escritura Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Especifica si se aplica el contenedor de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subdesbordamiento. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Representa si el eje es visible. Lectura/escritura Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Especifica la distancia de las etiquetas al eje. Aplicado a ejes de categoría o de fecha. El valor debe estar entre 0% y 1000%. Lectura/escritura UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Representa la base logarítmica. El valor predeterminado es 10. Lectura/escritura Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Representa el formato de las líneas de cuadrícula mayores en un eje de gráfico. Solo lectura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Representa el tipo de marca de graduación mayor para el eje especificado. Lectura/escritura [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Representa las unidades mayores para el eje de fechas o de valores. Lectura/escritura Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Representa la escala de la unidad mayor para el eje de fechas. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Representa el valor máximo en el eje de valores. Lectura/escritura Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Representa el formato de las líneas de cuadrícula menores en un eje de gráfico. Solo lectura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Representa el tipo de marca de graduación menor para el eje especificado. Lectura/escritura [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Representa las unidades menores para el eje de fechas o de valores. Lectura/escritura Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Representa la escala de la unidad mayor para el eje de fechas. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Representa el valor mínimo en el eje de valores. Lectura/escritura Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Representa la cadena de formato para las etiquetas del eje. Lectura/escritura String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Especifica el número de contenedores cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByNumberOfBins. Aplicado a ejes de categoría. Se usa solo con series Histogram o HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Especifica el valor personalizado del contenedor de desbordamiento. Aplicado cuando la propiedad IsAutomaticOverflowBin se establece en false y la propiedad IsOverflowBin es true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Representa la posición del eje. Lectura/escritura [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Representa si se muestran las líneas de cuadrícula mayores. Solo lectura Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Representa si se muestran las líneas de cuadrícula menores. Solo lectura Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Lectura/escritura [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Representa el ángulo de rotación de las etiquetas de graduación. Lectura/escritura Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Especifica cuántas etiquetas de graduación omitir entre las que se dibujan. Lectura/escritura UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Especifica cuántas marcas de graduación se deben omitir antes de dibujar la siguiente. Aplicado a ejes de categoría o de series. Lectura/escritura UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Obtiene el título del eje. Solo lectura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Especifica el valor personalizado del contenedor de subdesbordamiento. Aplicado cuando la propiedad IsAutomaticUnderflowBin se establece en false y la propiedad IsUnderflowBin es true. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Establece la propiedad IAxis.CategoryAxisType con un valor determinado automáticamente en función de los datos del eje. |

### Ver también

* interfaz [IFormattedTextContainer](../iformattedtextcontainer)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->