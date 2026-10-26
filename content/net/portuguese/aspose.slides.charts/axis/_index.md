---
title: Axis
second_title: Referência da API Aspose.Sildes para .NET
description: Encapsula o objeto que representa o eixo de um gráfico.
type: docs
weight: 1180
url: /pt/aspose.slides.charts/axis/
---
## Axis classe

Encapsula o objeto que representa o eixo de um gráfico.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Especifica a unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Especifica a escala da unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Especifica o valor máximo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Especifica a unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Especifica a escala da unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Especifica o valor mínimo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado à categoria. Usado apenas com séries Histogram ou HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Representa se o eixo de valores cruza o eixo de categoria entre as categorias. Esta propriedade se aplica apenas a eixos de categoria e não se aplica a gráficos 3-D. Leitura/gravação Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Especifica a menor unidade de tempo representada no eixo de data. Leitura/gravação [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Especifica a largura do bin quando o valor da propriedade AggregationType é definido como AxisAggregationType.ByBinWidth. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Especifica o tipo do eixo de categoria. Leitura/gravação [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Retorna o gráfico pai. Somente leitura [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Representa o ponto no eixo onde o eixo perpendicular o cruza. Leitura/gravação Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Representa o CrossType no eixo especificado onde o outro eixo o cruza. Leitura/gravação [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Especifica o valor de escala das unidades de exibição para o eixo de valor. Leitura/gravação [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Representa o formato do eixo. Somente leitura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Determina se um eixo possui um título visível. Leitura/gravação Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indica se a unidade principal do eixo é atribuída automaticamente. Leitura/gravação Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indica se o valor máximo é atribuído automaticamente. Leitura/gravação Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indica se a unidade secundária do eixo é atribuída automaticamente. Leitura/gravação Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indica se o valor mínimo é atribuído automaticamente. Leitura/gravação Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Especifica o valor automático do bin de estouro. Se false: use a propriedade OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Especifica o valor automático de espaçamento de rótulos de marcação. Se false: use a propriedade TickLabelSpacing. Leitura/gravação Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Especifica o valor automático de espaçamento de marcas de escala. Se false: use a propriedade TickMarksSpacing. Leitura/gravação Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Especifica o valor automático do bin de subfluxo. Se false: use a propriedade UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Representa se o tipo de escala do eixo de valor é logarítmico ou não. Leitura/gravação Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indica se o formato está vinculado aos dados de origem. Leitura/gravação Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Especifica se o bin de estouro é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de estouro. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Representa se o MS PowerPoint traça pontos de dados do último ao primeiro. Leitura/gravação Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Especifica se o bin de subfluxo é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de subfluxo. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Representa se o eixo está visível. Leitura/gravação Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Especifica a distância dos rótulos ao eixo. Aplicado a eixo de categoria ou data. O valor deve estar entre 0% e 1000%. Leitura/gravação UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Representa a base logarítmica. O valor padrão é 10. Leitura/gravação Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Representa o formato das linhas de grade principais em um eixo de gráfico. Somente leitura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Representa o tipo de marcação de escala principal para o eixo especificado. Leitura/gravação [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Representa as unidades principais para o eixo de data ou valor. Leitura/gravação Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Representa a escala da unidade principal para o eixo de data. Leitura/gravação [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Representa o valor máximo no eixo de valor. Leitura/gravação Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Representa o formato das linhas de grade secundárias em um eixo de gráfico. Somente leitura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Representa o tipo de marcação de escala secundária para o eixo especificado. Leitura/gravação [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Representa as unidades secundárias para o eixo de data ou valor. Leitura/gravação Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Representa a escala da unidade principal para o eixo de data. Leitura/gravação [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Representa o valor mínimo no eixo de valor. Leitura/gravação Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Representa a cadeia de formato para os Rótulos do Eixo. Leitura/gravação String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Especifica o número de bins quando o valor da propriedade AggregationType é definido como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Especifica o valor personalizado do bin de estouro. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e a propriedade IsOverflowBin é verdadeira. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Representa a posição do eixo. Leitura/gravação [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Para ocultar a linha de grade principal, defina MajorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill. Somente leitura Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Para ocultar a linha de grade secundária, defina MinorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill. Somente leitura Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Representa o formato do texto. Somente leitura [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Representa a posição dos rótulos das marcas de escala no eixo especificado. Leitura/gravação [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Representa o ângulo de rotação dos rótulos das marcas. Leitura/gravação Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. Aplicado ao eixo de categoria ou de série. Leitura/gravação UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado ao eixo de categoria ou de série. Leitura/gravação UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Obtém o título do eixo. Somente leitura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Especifica o valor personalizado do bin de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e a propriedade IsUnderflowBin é verdadeira. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Define a propriedade IAxis.CategoryAxisType com um valor que é determinado automaticamente com base nos dados do eixo. |

### Veja Também

* classe [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* classe [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->