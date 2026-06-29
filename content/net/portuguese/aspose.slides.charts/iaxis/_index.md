---
title: IAxis
second_title: Referência da API Aspose.Sildes para .NET
description: Encapsula o objeto que representa o eixo de um gráfico.
type: docs
weight: 1690
url: /pt/aspose.slides.charts/iaxis/
---
## IAxis interface

Encapsula o objeto que representa o eixo de um gráfico.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Especifica a unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Especifica a escala da unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Especifica o valor máximo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Especifica a unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Especifica a escala da unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Especifica o valor mínimo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Representa o tipo de agregação do eixo de categorias (agrupar). Aplicado a categoria. Usado somente com séries Histogram ou HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permite obter a interface base IFormattedTextContainer. Somente leitura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Representa se o eixo de valores cruza o eixo de categorias entre categorias. Esta propriedade se aplica somente a eixos de categorias e não se aplica a gráficos 3-D. Leitura/Gravação Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Especifica a menor unidade de tempo representada no eixo de data. Leitura/Gravação [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Especifica a largura do intervalo quando a propriedade AggregationType está definida como AxisAggregationType.ByBinWidth. Aplicado a eixos de categorias. Usado somente com séries Histogram ou HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Especifica o tipo do eixo de categorias. Leitura/Gravação [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Representa o ponto no eixo onde o eixo perpendicular o cruza. Leitura/Gravação Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Representa o CrossType no eixo especificado onde o outro eixo o cruza. Leitura/Gravação [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Especifica o valor de escala das unidades de exibição para o eixo de valores. Leitura/Gravação [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Representa o formato do eixo. Somente leitura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Determina se o eixo tem um título visível. Leitura/Gravação Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indica se a unidade principal do eixo é atribuída automaticamente. Leitura/Gravação Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indica se o valor máximo é atribuído automaticamente. Leitura/Gravação Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indica se a unidade secundária do eixo é atribuída automaticamente. Leitura/Gravação Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indica se o valor mínimo é atribuído automaticamente. Leitura/Gravação Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Especifica o valor automático do intervalo de estouro. Se false: use a propriedade OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Especifica o valor automático de espaçamento de rótulos de marcação. Se false: use a propriedade TickLabelSpacing. Leitura/Gravação Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Especifica o valor automático de espaçamento das marcas de escala. Se false: use a propriedade TickMarksSpacing. Leitura/Gravação Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Especifica o valor automático do intervalo de subfluxo. Se false: use a propriedade UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Representa se o tipo de escala do eixo de valores é logarítmico ou não. Leitura/Gravação Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indica se o formato está vinculado aos dados de origem. Leitura/Gravação Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Especifica se o intervalo de estouro está aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor de estouro. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Representa se o PowerPoint da MS traça os pontos de dados do último ao primeiro. Leitura/Gravação Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Especifica se o intervalo de subfluxo está aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor de subfluxo. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Representa se o eixo está visível. Leitura/Gravação Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Especifica a distância dos rótulos do eixo. Aplicado a eixo de categoria ou data. O valor deve estar entre 0 % e 1000 %. Leitura/Gravação UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Representa a base logarítmica. O valor padrão é 10. Leitura/Gravação Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Representa o formato das linhas de grade principais em um eixo de gráfico. Somente leitura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Representa o tipo de marca de escala principal para o eixo especificado. Leitura/Gravação [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Representa as unidades principais para o eixo de data ou valor. Leitura/Gravação Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Representa a escala da unidade principal para o eixo de data. Leitura/Gravação [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Representa o valor máximo no eixo de valores. Leitura/Gravação Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Representa o formato das linhas de grade secundárias em um eixo de gráfico. Somente leitura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Representa o tipo de marca de escala secundária para o eixo especificado. Leitura/Gravação [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Representa as unidades secundárias para o eixo de data ou valor. Leitura/Gravação Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Representa a escala da unidade principal para o eixo de data. Leitura/Gravação [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Representa o valor mínimo no eixo de valores. Leitura/Gravação Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Representa a cadeia de formato para os rótulos do eixo. Leitura/Gravação String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Especifica o número de intervalos quando a propriedade AggregationType está definida como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categorias. Usado somente com séries Histogram ou HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Especifica o valor customizado do intervalo de estouro. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e IsOverflowBin é true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Representa a posição do eixo. Leitura/Gravação [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Representa se as linhas de grade principais são exibidas. Somente leitura Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Representa se as linhas de grade secundárias são exibidas. Somente leitura Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Representa a posição dos rótulos das marcas de escala no eixo especificado. Leitura/Gravação [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Representa o ângulo de rotação dos rótulos das marcas de escala. Leitura/Gravação Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Especifica quantos rótulos de marca de escala pular entre os que são desenhados. Leitura/Gravação UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado a eixo de categoria ou série. Leitura/Gravação UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Obtém o título do eixo. Somente leitura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Especifica o valor customizado do intervalo de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e IsUnderflowBin é true. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Define a propriedade IAxis.CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo. |

### Ver também

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* espaço de nomes [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->