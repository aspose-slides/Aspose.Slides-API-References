---
title: IAxis
second_title: Referencia de API de Aspose.Slides para .NET
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
weight: 1630
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
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Especifica la unidad mayor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Especifica la escala de la unidad mayor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Especifica el valor máximo actual en el eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Especifica la unidad menor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Especifica la escala de la unidad menor actual del eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Especifica el valor mínimo actual en el eje. Llama al método IChart.ValidateChartLayout() previamente para obtener el valor actual. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Representa el tipo de agregación de ejes de categoría (agrupamiento). Aplicado a la categoría. Utilizado solo con series de Histograma o HistogramaPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Representa si el eje de valor cruza el eje de categoría entre categorías. Esta propiedad se aplica solo a ejes de categoría y no se aplica a gráficos en 3D. Booleano de lectura/escritura. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Especifica la unidad de tiempo más pequeña que está representada en el eje de fecha. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Especifica el ancho del bin cuando el valor de la propiedad AggregationType está establecido en AxisAggregationType.ByBinWidth. Aplicado a ejes de categoría. Utilizado solo con series de Histograma o HistogramaPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Especifica el tipo de eje de categoría. Lectura/escritura [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Representa el punto en el eje donde el eje perpendicular lo cruza. Lectura/escritura Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Representa el CrossType en el eje especificado donde el otro eje cruza. Lectura/escritura [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Especifica el valor de escalado de las unidades de visualización para el eje de valores. Lectura/escritura [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Representa el formato del eje. Solo lectura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Determina si un eje tiene un título visible. Booleano de lectura/escritura. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indica si la unidad mayor del eje es asignada automáticamente. Booleano de lectura/escritura. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indica si el valor máximo es asignado automáticamente. Booleano de lectura/escritura. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indica si la unidad menor del eje es asignada automáticamente. Booleano de lectura/escritura. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indica si el valor mínimo es asignado automáticamente. Booleano de lectura/escritura. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Especifica el valor del bin de desbordamiento automático. Si es falso: usa la propiedad OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Especifica el valor automático del espaciado de etiquetas de graduación. Si es falso: usa la propiedad TickLabelSpacing. Booleano de lectura/escritura. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Especifica el valor automático del espaciado de marcas de graduación. Si es falso: usa la propiedad TickMarksSpacing. Booleano de lectura/escritura. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Especifica el valor del bin de subdesbordamiento automático. Si es falso: usa la propiedad UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Representa si el tipo de escala del eje de valor es logarítmica o no. Booleano de lectura/escritura. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indica si el formato está vinculado a los datos de origen. Booleano de lectura/escritura. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Especifica si se aplica el bin de desbordamiento. Utiliza IsAutomaticOverflowBin y OverflowBin para ajustar el valor del bin de desbordamiento. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Representa si MS PowerPoint traza los puntos de datos de último a primero. Booleano de lectura/escritura. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Especifica si se aplica el bin de subdesbordamiento. Utiliza IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del bin de subdesbordamiento. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Representa si el eje es visible. Booleano de lectura/escritura. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Especifica la distancia de las etiquetas desde el eje. Aplicado a ejes de categoría o de fecha. El valor debe estar entre 0% y 1000%. Lectura/escritura UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Representa la base logarítmica. El valor predeterminado es 10. Lectura/escritura Doble. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Representa el formato de las líneas de cuadrícula mayores en un eje de gráfico. Solo lectura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Representa el tipo de marca de graduación mayor para el eje especificado. Lectura/escritura [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Representa las unidades mayores para el eje de fecha o valor. Lectura/escritura Doble. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Representa la escala de la unidad mayor para el eje de fecha. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Representa el valor máximo en el eje de valores. Lectura/escritura Doble. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Representa el formato de las líneas de cuadrícula menores en un eje de gráfico. Solo lectura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Representa el tipo de marca de graduación menor para el eje especificado. Lectura/escritura [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Representa las unidades menores para el eje de fecha o valor. Lectura/escritura Doble. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Representa la escala de la unidad mayor para el eje de fecha. Lectura/escritura [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Representa el valor mínimo en el eje de valores. Lectura/escritura Doble. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Representa la cadena de formato para las Etiquetas de Eje. Lectura/escritura Cadena. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Especifica el número de bins cuando el valor de la propiedad AggregationType está establecido en AxisAggregationType.ByNumberOfBins. Aplicado a ejes de categoría. Utilizado solo con series de Histograma o HistogramaPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Especifica el valor personalizado del bin de desbordamiento. Aplicado cuando la propiedad IsAutomaticOverflowBin está establecida en falso y la propiedad IsOverflowBin es igual a verdadero. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Representa la posición del eje. Lectura/escritura [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Representa si las líneas de cuadrícula mayores se muestran. Booleano de solo lectura. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Representa si las líneas de cuadrícula menores se muestran. Booleano de solo lectura. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Representa la posición de las etiquetas de la marca de graduación en el eje especificado. Lectura/escritura [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Representa el ángulo de rotación de las etiquetas de graduación Lectura/escritura Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Especifica cuántas etiquetas de graduación omitir entre la etiqueta que se dibuja. Lectura/escritura UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Especifica cuántas marcas de graduación se omitirán antes de que se dibuje la siguiente. Aplicado a ejes de categoría o serie. Lectura/escritura UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Obtiene el título del eje. Solo lectura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Especifica el valor personalizado del bin de subdesbordamiento. Aplicado cuando la propiedad IsAutomaticUnderflowBin está establecida en falso y la propiedad IsUnderflowBin es igual a verdadero. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Establece la propiedad IAxis.CategoryAxisType con un valor determinado automáticamente en función de los datos del eje. |

### Véase también

* interfaz [IFormattedTextContainer](../iformattedtextcontainer)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->