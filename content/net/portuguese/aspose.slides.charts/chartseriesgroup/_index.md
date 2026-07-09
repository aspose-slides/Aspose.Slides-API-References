---
title: ChartSeriesGroup
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um grupo de séries.
type: docs
weight: 1460
url: /pt/aspose.slides.charts/chartseriesgroup/
---
## classe ChartSeriesGroup

Representa um grupo de séries.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Leitura/gravação [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Especifica o fator de escala para o gráfico de bolhas (pode estar entre 0 e 300% do tamanho padrão). Leitura/gravação Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Retorna o gráfico pai. Somente leitura [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 0 e 90% do tamanho da área de plotagem). Leitura/gravação Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Obtém ou define o ângulo do primeiro segmento de pizza ou rosca, em graus (no sentido horário a partir de cima, de 0 a 360 graus). Leitura/gravação UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Leitura/gravação UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Especifica o espaço entre agrupamentos de barras ou colunas, como porcentagem da largura da barra ou coluna. Leitura/gravação UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Verdadeiro se o gráfico tem linhas de série. Aplicado a gráficos de barras empilhadas e OfPie. Leitura/gravação Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Especifica o formato HiLowLines. HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de dados na série tem uma cor diferente. Leitura/gravação Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Obtém o elemento no índice especificado. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Especifica o quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). - -100%: Espaçamento máximo (as barras estão completamente separadas). - 0%: As barras são colocadas lado a lado sem sobreposição ou espaçamento. - 100%: Sobreposição máxima (as barras se sobrepõem completamente). Esta propriedade é leitura/gravação SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico de pizza-em-pizza ou barra-em-pizza. Leitura/gravação [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | As informações de divisão personalizada para um gráfico de pizza-em-pizza ou barra-em-pizza com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico de pizza-em-pizza ou barra-em-pizza. Somente leitura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Especifica um valor que será usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico de pizza-em-pizza ou barra-em-pizza. É usado juntamente com a propriedade PieSplitBy. Leitura/gravação Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica se as séries deste grupo são plotadas no eixo secundário. Somente leitura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Especifica o tamanho da segunda pizza ou barra de um gráfico de pizza-em-pizza ou barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode estar entre 5 e 200%). Leitura/gravação UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Retorna uma coleção de séries. Somente leitura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Retorna um tipo deste grupo de séries. Somente leitura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fornece acesso às barras de alta/baixa de um gráfico de linha ou de ação. Somente leitura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observações

1) Consulte o resumo e as observações da classe ChartSeriesGroupCollection e do enum CombinableSeriesTypesGroup. 2) O grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo (“propriedades do grupo de séries”). “Propriedades do grupo de séries” na classe ChartSeriesGroup são leitura/gravação. Cada uma das “propriedades do grupo de séries” pode ter uma projeção somente leitura na classe ChartSeries.

### Veja Também

* interface [IChartSeriesGroup](../ichartseriesgroup)
* espaço de nomes [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->