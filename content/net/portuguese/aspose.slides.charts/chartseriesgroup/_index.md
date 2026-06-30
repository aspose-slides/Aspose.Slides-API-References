---
title: ChartSeriesGroup
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um grupo de séries.
type: docs
weight: 1440
url: /pt/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Representa um grupo de séries.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Leitura/Gravação [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Especifica o fator de escala para o gráfico de bolhas (pode estar entre 0 e 300 por cento do tamanho padrão). Leitura/Gravação Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Retorna o gráfico pai. Somente leitura [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Especifica o tamanho do furo em um gráfico de rosca (pode estar entre 0 e 90 por cento do tamanho da área de plotagem). Leitura/Gravação Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtém ou define o ângulo da primeira fatia de gráfico de pizza ou rosca, em graus (horário a partir de cima, de 0 a 360 graus). Leitura/Gravação UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Leitura/Gravação UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Especifica o espaço entre grupos de barras ou colunas, como porcentagem da largura da barra ou coluna. Leitura/Gravação UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Verdadeiro se o gráfico tem linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Leitura/Gravação Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Especifica o formato HiLowLines. HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de dados na série tem uma cor diferente. Leitura/Gravação Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtém o elemento no índice especificado. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Especifica o quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). - -100%: Espaçamento máximo (barras totalmente separadas). - 0%: Barras posicionadas lado a lado sem sobreposição ou espaçamento. - 100%: Sobreposição máxima (barras totalmente sobrepostas). Esta propriedade é Leitura/Gravação SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. Leitura/Gravação [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | As informações de divisão personalizada para um gráfico pizza-em-pizza ou barra-em-pizza com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra. Somente leitura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Especifica um valor que será usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. É usado junto com a propriedade PieSplitBy. Leitura/Gravação Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica se as séries deste grupo são plotadas no eixo secundário. Somente leitura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Especifica o tamanho da segunda pizza ou barra de um gráfico pizza-em-pizza ou barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode estar entre 5 e 200 por cento). Leitura/Gravação UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Retorna uma coleção de séries. Somente leitura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Retorna o tipo deste grupo de séries. Somente leitura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fornece acesso às barras de alta/baixa de gráfico de linha ou de ações. Somente leitura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observações

1) Consulte o resumo e as observações para ChartSeriesGroupCollection classe e CombinableSeriesTypesGroup enum. 2) O grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo (“propriedades do grupo de séries”). As “propriedades do grupo de séries” em ChartSeriesGroup classe são Leitura/Gravação. Cada uma das “propriedades do grupo de séries” pode ter uma projeção Somente leitura na classe ChartSeries.

### Veja Também

* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->