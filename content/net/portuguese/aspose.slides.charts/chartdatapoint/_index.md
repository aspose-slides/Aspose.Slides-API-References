---
title: ChartDataPoint
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um ponto de dados da série.
type: docs
weight: 1340
url: /pt/aspose.slides.charts/chartdatapoint/
---
## classe ChartDataPoint

Representa um ponto de dados da série.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Obtém o tamanho de bolha em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Obtém o valor em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Obtém o valor X em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Obtém o valor Y em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Retorna o valor de cor do ponto de dados do gráfico. Usado com gráficos de Mapa. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Retorna o contêiner dos níveis do ponto de dados. Aplicado para séries Treeamp e Sunburst. A indexação dos níveis dos pontos de dados começa em zero. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Representa os valores das barras de erro da série no caso do tipo de valor Custom. Somente leitura [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Especifica a quantidade que o ponto de dados deve ser movido a partir do centro da fatia. Leitura/gravação Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Representa as propriedades de formatação. Leitura/gravação [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. Leitura/gravação Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Especifica que as bolhas têm um efeito 3-D aplicado a elas. Leitura/gravação Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Rótulo. Somente leitura [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Especifica um marcador de dados. Somente leitura [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Somente leitura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Define o ponto de dados como total. Aplicado apenas para o tipo de série Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Retorna o valor de tamanho do ponto de dados do gráfico. Usado com gráficos Treemap e Sunburst. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Valor. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Somente leitura [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Retorna uma cor automática do ponto de dados com base no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e estilo do gráfico. Esta cor é usada por padrão se FillType for igual a NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Remove DataPoint da série do gráfico. |

### Veja Também

* interface [IChartDataPoint](../ichartdatapoint)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->