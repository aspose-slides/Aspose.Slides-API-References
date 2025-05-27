---
title: Eje
second_title: Referencia API de Aspose.Slides para .NET
description: Encapsula el objeto que representa un eje de gráficos.
type: docs
weight: 1100
url: /es/aspose.slides.charts/axis/
---

## Clase Axis

Encapsula el objeto que representa un eje de gráfico.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Especifica la unidad mayor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Especifica la escala de unidad mayor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Especifica el valor máximo actual en el eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Especifica la unidad menor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Especifica la escala de unidad menor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Especifica el valor mínimo actual en el eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Representa el tipo de agregación del eje de categoría (agrupación). Se aplica a la categoría. Se utiliza solo con series de Histograma o HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad se aplica solo a los ejes de categoría y no se aplica a gráficos en 3-D. Lectura/escritura Booleano. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Especifica la unidad de tiempo más pequeña que se representa en el eje de fecha. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByBinWidth. Se aplica a los ejes de categoría. Se utiliza solo con series de Histograma o HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Especifica el tipo de eje de categoría. Lectura/escritura [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Devuelve el gráfico padre. Solo lectura [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Representa el punto en el eje donde el eje perpendicular lo cruza. Lectura/escritura Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Representa el CrossType en el eje especificado donde el otro eje cruza. Lectura/escritura [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Especifica el valor de escalado de las unidades de visualización para el eje de valores. Lectura/escritura [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Representa el formato del eje. Solo lectura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Determina si un eje tiene un título visible. Lectura/escritura Booleano. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indica si la unidad mayor del eje se asigna automáticamente. Lectura/escritura Booleano. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indica si el valor máximo se asigna automáticamente. Lectura/escritura Booleano. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indica si la unidad menor del eje se asigna automáticamente. Lectura/escritura Booleano. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indica si el valor mínimo se asigna automáticamente. Lectura/escritura Booleano. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Especifica el valor de contenedor de desbordamiento automático. Si es falso: usa la propiedad OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Especifica el valor de espaciado automático de etiquetas de marcas. Si es falso: usa la propiedad TickLabelSpacing. Lectura/escritura Booleano. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Especifica el valor de espaciado automático de marcas. Si es falso: usa la propiedad TickMarksSpacing. Lectura/escritura Booleano. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Especifica el valor de contenedor de subdesbordamiento automático. Si es falso: usa la propiedad UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Representa si el tipo de escala del eje de valores es logarítmica o no. Lectura/escritura Booleano. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indica si el formato está vinculado a datos de origen. Lectura/escritura Booleano. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Especifica si se aplica el contenedor de desbordamiento. Usa IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Representa si MS PowerPoint dibuja los puntos de datos de atrás hacia adelante. Lectura/escritura Booleano. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Especifica si se aplica el contenedor de subdesbordamiento. Usa IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subdesbordamiento. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Representa si el eje es visible. Lectura/escritura Booleano. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Especifica la distancia de las etiquetas desde el eje. Se aplica a los ejes de categoría o fecha. El valor debe estar entre 0% y 1000%. Lectura/escritura UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Representa la base logarítmica. El valor predeterminado es 10. Lectura/escritura Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Representa el formato de las líneas de cuadrícula mayores en un eje de gráfico. Solo lectura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Representa el tipo de marca mayor para el eje especificado. Lectura/escritura [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Representa las unidades mayores para el eje de fecha o valor. Lectura/escritura Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Representa la escala de unidad mayor para el eje de fecha. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Representa el valor máximo en el eje de valores. Lectura/escritura Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Representa el formato de las líneas de cuadrícula menores en un eje de gráfico. Solo lectura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Representa el tipo de marca menor para el eje especificado. Lectura/escritura [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Representa las unidades menores para el eje de fecha o valor. Lectura/escritura Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Representa la escala de unidad menor para el eje de fecha. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Representa el valor mínimo en el eje de valores. Lectura/escritura Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Representa la cadena de formato para las etiquetas del eje. Lectura/escritura String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Especifica el número de contenedores cuando el valor de la propiedad AggregationType se establece en AxisAggregationType.ByNumberOfBins. Se aplica a los ejes de categoría. Se utiliza solo con series de Histograma o HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Especifica el valor personalizado del contenedor de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin se establece en falso y la propiedad IsOverflowBin es igual a verdadero. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Representa la posición del eje. Lectura/escritura [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Para ocultar la línea de cuadrícula mayor, establece MajorGridLinesFormat.Line.FillFormat.FillType en FillType.NoFill. Solo lectura Booleano. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Para ocultar la línea de cuadrícula menor, establece MinorGridLinesFormat.Line.FillFormat.FillType en FillType.NoFill. Solo lectura Booleano. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Representa el formato del texto. Solo lectura [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Representa la posición de las etiquetas de marcas en el eje especificado. Lectura/escritura [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Representa el ángulo de rotación de las etiquetas de marca. Lectura/escritura Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Especifica cuántas etiquetas de marcas omitir entre la etiqueta que se dibuja. Se aplica a ejes de categoría o de series. Lectura/escritura UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Especifica cuántas marcas se deben omitir antes de que se dibuje la siguiente. Se aplica a ejes de categoría o de series. Lectura/escritura UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Obtiene el título del eje. Solo lectura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Especifica el valor personalizado del contenedor de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin se establece en falso y la propiedad IsUnderflowBin es igual a verdadero. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Establece la propiedad IAxis.CategoryAxisType con un valor que se determina automáticamente basado en los datos del eje. |

### Véase También

* clase [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* clase [AxesManager](../axesmanager)
* interfaz [IAxis](../iaxis)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->