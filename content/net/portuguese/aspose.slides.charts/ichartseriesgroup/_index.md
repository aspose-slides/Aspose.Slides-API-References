---
title: IChartSeriesGroup
second_title: Referência da API Aspose.Sildes for .NET
description: Representa um grupo de séries.
type: docs
weight: 1970
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
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Especifica como os valores de tamanho de bolha são representados no gráfico de bolhas. Leitura/Gravação [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Especifica o fator de escala para o gráfico de bolhas (pode estar entre 0 e 300 por cento do tamanho padrão). Leitura/Gravação Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 10 e 90 por cento do tamanho da área de plotagem). Leitura/Gravação Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Obtém ou define o ângulo da primeira fatia de gráfico de pizza ou rosca, em graus (no sentido horário a partir do topo, de 0 a 360 graus). Leitura/Gravação UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Obtém ou define a distância entre séries de dados em um gráfico 3D, como porcentagem da largura do marcador. O valor deve estar entre 0 e 500. Leitura/Gravação UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Obtém ou define o espaço entre agrupamentos de barras ou colunas, como porcentagem da largura da barra ou coluna. O valor deve estar entre 0 e 500. Leitura/Gravação UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barras empilhadas e OfPie. Leitura/Gravação Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Especifica o formato HiLowLines. HiLowLines aplicadas com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Especifica que cada marcador de dados na série tem uma cor diferente. Leitura/Gravação Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Obtém o elemento no índice especificado. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). - -100%: Espaçamento máximo (barras completamente separadas). - 0%: Barras posicionadas lado a lado sem sobreposição ou espaçamento. - 100%: Sobreposição máxima (barras completamente sobrepostas). Esta propriedade é leitura/gravação SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Leitura/Gravação [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | As informações de divisão personalizada para um gráfico pie-of-pie ou bar-of-pie com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Somente leitura [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Especifica um valor que será usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. É usado juntamente com a propriedade PieSplitBy. Leitura/Gravação Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indica se as séries deste grupo são plotadas no eixo secundário. Somente leitura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Especifica o tamanho da segunda pizza ou barra de um gráfico pie-of-pie ou bar-of-pie, como porcentagem do tamanho da primeira pizza (pode estar entre 5 e 200 por cento). Leitura/Gravação UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Retorna uma coleção somente leitura de séries de gráfico. Somente leitura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Retorna o tipo deste grupo de séries. Somente leitura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Fornece acesso às barras alta/baixa de gráfico de linha ou de ações. Somente leitura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Observações

1) Veja o resumo e as observações da classe ChartSeriesGroupCollection e do enum CombinableSeriesTypesGroup. 2) O grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo ("propriedades de grupo de séries"). As "propriedades de grupo de séries" na classe ChartSeriesGroup são leitura/gravação. Cada uma das "propriedades de grupo de séries" pode ter uma projeção somente leitura na classe ChartSeries.

### Veja também

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->