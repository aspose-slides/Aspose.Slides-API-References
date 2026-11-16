---
title: IChartDataPoint
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um ponto de dados da série.
type: docs
weight: 1840
url: /pt/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint interface

Represents series data point.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Retorna a interface IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Obtém o tamanho da bolha de um ponto de dados do gráfico. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Obtém o tamanho da bolha em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Obtém o valor em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Obtém o valor X em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Obtém o valor Y em cache de um ponto de dados do gráfico. Somente leitura [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Obtém o valor de cor de um ponto de dados do gráfico. Usado com gráficos de mapa. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Retorna o contêiner de níveis de ponto de dados. Aplicado para séries Treeamp e Sunburst. A indexação dos níveis de ponto de dados começa em zero. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Representa os valores de barras de erro da série no caso de tipo de valor Custom. Somente leitura [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Especifica a quantidade que o ponto de dados deve ser movido a partir do centro da pizza. Leitura/gravação Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Representa as propriedades de formatação. Leitura/gravação [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Determina a qual coleção de filhos do pai este ponto de dados se aplica. Leitura UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. Leitura/gravação Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Especifica que as bolhas têm um efeito 3D aplicado a elas. Leitura/gravação Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Representa o rótulo do ponto de dados do gráfico. Somente leitura [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Especifica um marcador de dados. Somente leitura [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Somente leitura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Define o ponto de dados como total. Aplicado somente para o tipo de série Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Obtém o valor de tamanho de um ponto de dados do gráfico. Usado com gráficos Treemap e Sunburst. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Obtém o valor de um ponto de dados do gráfico. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Obtém o valor x de um ponto de dados do gráfico. Somente leitura [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Obtém o valor y de um ponto de dados do gráfico. Somente leitura [`IDoubleChartValue`](../idoublechartvalue). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Retorna uma cor automática do ponto de dados com base no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e estilo do gráfico. Essa cor é usada por padrão se FillType for igual a NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Remove DataPoint da série do gráfico. |

### Veja Também

* interface [IActualLayout](../iactuallayout)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->