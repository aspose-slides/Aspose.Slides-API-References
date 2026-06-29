---
title: ChartSeries
second_title: Referência da API Aspose.Sildes para .NET
description: Representa uma série de gráfico.
type: docs
weight: 1420
url: /pt/aspose.slides.charts/chartseries/
---
## classe ChartSeries

Representa uma série de gráfico.

```csharp
public class ChartSeries : IChartSeries
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Especifica a forma de uma série de um gráfico de barras 3-D. Alterar o valor desta propriedade pode causar a mudança automática do Tipo da série. Leitura/gravação [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Especifica como os valores de tamanho de bolha são representados no gráfico de bolhas. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.BubbleSizeRepresentation leitura/gravação para alterar o valor. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Especifica o fator de escala para o gráfico de bolhas (pode variar entre 0 e 300 % do tamanho padrão). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.BubbleSizeScale leitura/gravação para alterar o valor. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Retorna o gráfico pai. Somente leitura [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Retorna a coleção de pontos de dados desta série. Somente leitura [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Especifica o tamanho do buraco em um gráfico de rosca (pode variar entre 10 e 90 % do tamanho da área de plotagem). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.DoughnutHoleSize leitura/gravação para alterar o valor. Somente leitura Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Representa ErrorBars da série com direção X. ErrorBars com direção X estão disponíveis para séries dos tipos area, bar, scatter e bubble. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados use a coleção DataPoints para especificar o valor (com a propriedade [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Somente leitura [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Representa ErrorBars da série com direção Y. ErrorBars com direção Y estão disponíveis para séries dos tipos area, bar, line, scatter e bubble. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados use a coleção DataPoints para especificar o valor (com a propriedade [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Somente leitura [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como porcentagem do diâmetro da pizza. Leitura/gravação Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Especifica o ângulo da primeira fatia de um gráfico de pizza ou rosca, em graus (no sentido horário a partir de cima, de 0 a 360 graus). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.FirstSliceAngle leitura/gravação para alterar o valor. Somente leitura UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Retorna o formato de uma série. Somente leitura [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.GapDepth leitura/gravação para alterar o valor. Somente leitura Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Especifica o espaço entre grupos de barras ou colunas, como porcentagem da largura da barra ou coluna. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.GapWidth leitura/gravação para alterar o valor. Somente leitura Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Determina se há linhas de série para esta série e séries afins. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.HasSeriesLines leitura/gravação para alterar o valor. Use a propriedade ParentSeriesGroup.SeriesLinesFormat para formatar as linhas de série. Somente leitura Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Determina se o gráfico de Linha ou de Ações possui barras de alta/baixa. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.UpDownBars.HasUpDownBars leitura/gravação para alterar o valor. Use a propriedade ParentSeriesGroup.UpDownBars para formatar as barras de alta/baixa. Somente leitura Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Especifica cor sólida invertida para a série. Para aplicar a definição de cor, defina o FillType do formato da série para FillType.Solid. Leitura/gravação [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. Leitura/gravação Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Especifica que cada marcador de dados na série tem uma cor diferente. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.IsColorVaried leitura/gravação para alterar o valor. Somente leitura Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Retorna os Labels de uma série. Somente leitura [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker. Somente leitura [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Retorna o nome da série. Somente leitura [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Leitura/gravação String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Leitura/gravação String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Leitura/gravação String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Leitura/gravação String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Retorna a ordem de uma série. Leitura/gravação Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Especifica quanto as barras e colunas se sobrepõem em gráficos 2-D, como porcentagem (de -100 % a 100 %). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Para alterar o valor, use a propriedade !:ParentSeriesGroup.Overlap leitura/gravação. Somente leitura SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Representa o layout dos rótulos de categoria pai. Aplica-se apenas a gráficos Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Somente leitura [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Especifica como determinar quais pontos de dados estão no segundo círculo ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.PieSplitBy leitura/gravação para alterar o valor. Somente leitura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | As informações personalizadas de divisão para um gráfico de pizza-de-pizza ou barra-de-pizza com divisão personalizada. Contém pontos de dados que devem ser desenhados no segundo círculo ou barra. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Somente leitura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Especifica um valor que deve ser usado para determinar quais pontos de dados estão no segundo círculo ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. É usado juntamente com a propriedade PieSplitBy. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.PieSplitPosition leitura/gravação para alterar o valor. Somente leitura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Indica se esta série é plotada em um eixo secundário. Leitura/gravação Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Representa o método de quartil. Aplica-se apenas a gráficos BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Representa a entrada de legenda relacionada a esta série. Somente leitura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Especifica o tamanho do segundo círculo ou barra de um gráfico de pizza-de-pizza ou barra-de-pizza, como porcentagem do tamanho do primeiro círculo (pode variar entre 5 e 200 %). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo pai – é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo pai. Use a propriedade ParentSeriesGroup.SecondPieSize leitura/gravação para alterar o valor. Somente leitura UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Representa linhas de conexão. Aplica-se apenas a gráficos Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Representa pontos internos. Verdadeiro se pontos internos são mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Representa a linha média. Verdadeiro se a linha média é mostrada no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Representa marcadores de média. Verdadeiro se os marcadores de média são mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Representa pontos outlier. Verdadeiro se pontos outlier são mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Representa suavização de curva. Verdadeiro se a suavização de curva está ativada para o gráfico de linhas ou de dispersão. Aplica-se apenas a gráficos de linhas e dispersão conectados por linhas. Leitura/gravação Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Coleção de linhas de tendência da série. Somente leitura [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Retorna um tipo desta série. Leitura/gravação [`ChartType`](../charttype). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Retorna uma cor automática da série baseada no índice da série e no estilo do gráfico. Esta cor é usada por padrão se FillType for NotDefined. |

### Veja Também

* interface [IChartSeries](../ichartseries)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->