---
title: IChartSeriesGroup
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um grupo de séries.
type: docs
weight: 1950
url: /pt/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Representa um grupo de séries.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Permite obter a interface base IChartComponent. Somente leitura [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Leitura/gravação [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Especifica o fator de escala para o gráfico de bolhas (pode estar entre 0 e 300 por cento do tamanho padrão). Leitura/gravação Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 10 e 90 por cento do tamanho da área de plotagem). Leitura/gravação Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtém ou define o ângulo da primeira fatia de pizza ou rosca, em graus (no sentido horário a partir de cima, de 0 a 360 graus). Leitura/gravação UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Leitura/gravação UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Especifica o espaço entre grupos de barras ou colunas, como porcentagem da largura da barra ou coluna. Leitura/gravação UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barras empilhadas e OfPie. Leitura/gravação Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Especifica o formato HiLowLines. HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de dados na série tem uma cor diferente. Leitura/gravação Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtém o elemento no índice especificado. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Especifica o quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). - -100%: Espaçamento máximo (as barras são completamente separadas). - 0%: As barras são posicionadas lado a lado sem sobreposição ou espaçamento. - 100%: Sobreposição máxima (as barras se sobrepõem completamente). Esta propriedade é leitura/gravação SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Leitura/gravação [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | As informações de divisão personalizada para um gráfico pie-of-pie ou bar-of-pie com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Somente leitura [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Especifica um valor que deve ser usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. É usado junto com a propriedade PieSplitBy. Leitura/gravação Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indica se as séries deste grupo são plotadas no eixo secundário. Somente leitura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Especifica o tamanho da segunda pizza ou barra de um gráfico pie-of-pie ou bar-of-pie, como porcentagem do tamanho da primeira pizza (pode estar entre 5 e 200 por cento). Leitura/gravação UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Retorna uma coleção somente leitura de séries de gráfico. Somente leitura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Retorna um tipo deste grupo de séries. Somente leitura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Fornece acesso às barras up/down de gráficos de linha ou de ações. Somente leitura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observações

1) Veja o resumo e as observações da classe ChartSeriesGroupCollection e do enum CombinableSeriesTypesGroup. 2) O grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo ("propriedades do grupo de séries"). "Propriedades do grupo de séries" na classe ChartSeriesGroup é leitura/gravação. Cada uma das "propriedades do grupo de séries" pode ter uma projeção somente leitura na classe ChartSeries.

### Ver Também

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->