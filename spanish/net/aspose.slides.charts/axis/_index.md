---
title: Axis
second_title: Referencia de la API de Aspose.Slides para .NET
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
weight: 1040
url: /es/net/aspose.slides.charts/axis/
---
## Axis class

Encapsula el objeto que representa el eje de un gráfico.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Especifica la unidad principal real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Especifica la escala de unidad principal real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Especifica el valor máximo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Especifica la unidad menor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Especifica la escala de unidad menor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Especifica el valor mínimo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Representa el tipo de agregación del eje de categoría (binning). Aplicado a la categoría. Usado con la serie Histogram o HistogramPareto solamente. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Representa si el eje de valor cruza el eje de categoría entre categorías. Esta propiedad se aplica solo a los ejes de categoría y no se aplica a los gráficos 3D. Lectura/escrituraBoolean . |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Especifica la unidad de tiempo más pequeña que se representa en el eje de fecha. Lectura/escritura[`TimeUnitType`](../timeunittype) . |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByBinWidth. Aplicado a ejes de categoría. Usado con la serie Histogram o HistogramPareto solamente. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Especifica el tipo del eje de categorías. Lectura/escritura[`CategoryAxisType`](../categoryaxistype) . |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Devuelve el gráfico principal. Solo lectura[`IChart`](../ichart) . |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Representa el punto del eje donde lo cruza el eje perpendicular. Lectura/escrituraSingle . |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Representa el CrossType en el eje especificado donde se cruza el otro eje. Lectura/escritura[`CrossesType`](../crossestype) . |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Especifica el valor de escala de las unidades de visualización para el eje de valor. Lectura/escritura[`DisplayUnitType`](../displayunittype) . |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Representa el formato del eje. Solo lectura[`IAxisFormat`](../iaxisformat) . |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Determina si un eje tiene un título visible. Lectura/escrituraBoolean . |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indica si se asigna automáticamente la unidad mayor del eje. Lectura/escrituraBoolean . |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indica si el valor máximo se asigna automáticamente. Lectura/escrituraBoolean . |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indica si se asigna automáticamente la unidad menor del eje. Lectura/escrituraBoolean . |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indica si el valor mínimo se asigna automáticamente. Lectura/escrituraBoolean . |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Especifica el valor del contenedor de desbordamiento automático. Si es falso: use la propiedad OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Especifica el valor de espaciado automático de etiquetas de marcas. Si es falso: use la propiedad TickLabelSpacing. Lectura/escrituraBoolean . |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Especifica el valor de espaciado automático de las marcas de graduación. Si es falso: use la propiedad TickMarksSpacing. Lectura/escrituraBoolean . |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Especifica el valor del contenedor de subdesbordamiento automático. Si es falso: use la propiedad UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura/escrituraBoolean . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indica si el formato es datos de origen vinculados. Lectura/escrituraBoolean . |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Especifica si se aplica el contenedor de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Representa si MS PowerPoint traza puntos de datos del último al primero. Lectura/escrituraBoolean . |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Especifica si se aplica el contenedor de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subdesbordamiento. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Representa si el eje es visible. Lectura/escrituraBoolean . |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Especifica la distancia de las etiquetas desde el eje. Aplicado a categoría o eje de fecha. El valor debe estar entre 0% y 1000%. Lectura/escrituraUInt16 . |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Representa la base logarítmica. El valor predeterminado es 10. Lectura/escrituraDouble . |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Representa el formato principal de las líneas de cuadrícula en un eje del gráfico. Solo lectura[`IChartLinesFormat`](../ichartlinesformat) . |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Representa el tipo de marca principal para el eje especificado. Lectura/escritura[`TickMarkType`](../tickmarktype) . |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Representa las unidades principales para el eje de fecha o valor. Lectura/escrituraDouble . |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Representa la escala de unidad mayor para el eje de fecha. Lectura/escritura[`TimeUnitType`](../timeunittype) . |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Representa el valor máximo en el eje de valores. Lectura/escrituraDouble . |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Representa el formato de líneas de cuadrícula menores en un eje de gráfico. Solo lectura[`IChartLinesFormat`](../ichartlinesformat) . |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Representa el tipo de marca de graduación menor para el eje especificado. Lectura/escritura[`TickMarkType`](../tickmarktype) . |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Representa las unidades menores para el eje de fecha o valor. Lectura/escrituraDouble . |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Representa la escala de unidad mayor para el eje de fecha. Lectura/escritura[`TimeUnitType`](../timeunittype) . |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Representa el valor mínimo en el eje de valores. Lectura/escrituraDouble . |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Representa la cadena de formato para las etiquetas de eje. Lectura/escrituraString . |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Especifica el número de contenedores cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByNumberOfBins. Aplicado a ejes de categoría. Usado con la serie Histogram o HistogramPareto solamente. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Especifica el valor personalizado del contenedor de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin se establece en falso y la propiedad IsOverflowBin es igual a verdadero. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Representa la posición del eje. Lectura/escritura[`AxisPositionType`](../axispositiontype) . |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Para ocultar la línea de cuadrícula principal, establezca MajorGridLinesFormat.Line.FillFormat.FillType en FillType.NoFill. Solo lecturaBoolean . |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Para ocultar la línea de cuadrícula secundaria, establezca MinorGridLinesFormat.Line.FillFormat.FillType en FillType.NoFill. Solo lecturaBoolean . |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Representa el formato de texto. Solo lectura[`IChartTextFormat`](../icharttextformat) . |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Representa la posición de las etiquetas de marcas en el eje especificado. Lectura/escritura[`TickLabelPositionType`](../ticklabelpositiontype) . |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Representa el ángulo de rotación de las etiquetas de marca. Lectura/escrituraSingle . |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Especifica cuántas etiquetas de marca se saltan entre las etiquetas que se dibujan. Aplicado al eje de categoría o serie. Lectura/escrituraUInt32 . |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Especifica cuántas marcas de verificación se omitirán antes de que se dibuje la siguiente . Aplicado al eje de categoría o serie. Lectura/escrituraUInt16 . |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Obtiene el título del eje. Solo lectura[`IChartTitle`](../icharttitle) . |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Especifica el valor personalizado del contenedor de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin se establece en falso y la propiedad IsUnderflowBin es igual a verdadero. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Establece la propiedad IAxis.CategoryAxisType con un valor que se determina automáticamente en función de los datos del eje. |

### Ver también

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
