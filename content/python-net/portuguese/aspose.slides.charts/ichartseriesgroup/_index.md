---
title: IChartSeriesGroup class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup classe

Representa um grupo de séries.

O tipo IChartSeriesGroup expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/type/) | Retorna um tipo deste grupo de séries.<br/>            Somente leitura [`CombinableSeriesTypesGroup`](/slides/python-net/pt/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indica se as séries deste grupo são plotadas em um eixo secundário.<br/>            Somente leitura **bool**. |
| [`series`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/series/) | Retorna uma coleção somente leitura de séries de gráfico.<br/>            Somente leitura [`IChartSeriesReadonlyCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Fornece acesso às barras up/down de gráficos de linha ou de ações.<br/>            Somente leitura [`IUpDownBarsManager`](/slides/python-net/pt/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/gap_width/) | Especifica o espaço entre grupos de barras ou colunas, como uma porcentagem da largura da barra ou coluna.<br/>            Leitura/Gravação **int**. |
| [`gap_depth`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D.<br/>            Leitura/Gravação **int**. |
| [`first_slice_angle`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Obtém ou define o ângulo da primeira fatia de gráfico de pizza ou rosca, <br/>            em graus (no sentido horário a partir de cima, de 0 a 360 graus).<br/>            Leitura/Gravação **int**. |
| [`is_color_varied`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Especifica que cada marcador de dados na série tem uma cor diferente.<br/>            Leitura/Gravação **bool**. |
| [`has_series_lines`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barras empilhadas e OfPie.<br/>            Leitura/Gravação **bool**. |
| [`overlap`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/overlap/) | Especifica o quanto as barras e colunas devem sobrepor em gráficos 2-D, como uma porcentagem (de -100% a 100%).<br/>             - -100%: Espaçamento máximo (barras totalmente separadas).<br/>             - 0%: Barras colocadas lado a lado sem sobreposição ou espaçamento.<br/>             - 100%: Sobreposição máxima (barras totalmente sobrepostas).<br/>             Esta propriedade é leitura/gravação **int**. |
| [`second_pie_size`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Especifica o tamanho da segunda pizza ou barra de um gráfico pizza-em-pizza ou <br/>            um gráfico barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode <br/>            estar entre 5 e 200 por cento).<br/>            Leitura/Gravação **int**. |
| [`pie_split_position`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Especifica um valor que será usado para determinar quais pontos de dados <br/>            estão na segunda pizza ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. <br/>            É usado junto com a propriedade PieSplitBy.<br/>            Leitura/Gravação **float**. |
| [`pie_split_by`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra <br/>            em um gráfico pizza-em-pizza ou barra-em-pizza.<br/>            Leitura/Gravação [`PieSplitType`](/slides/python-net/pt/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | As informações de divisão personalizada para um gráfico pizza-em-pizza ou barra-em-pizza com divisão personalizada.<br/>            Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico pizza-em-pizza ou <br/>            barra-em-pizza.<br/>            Somente leitura [`IPieSplitCustomPointCollection`](/slides/python-net/pt/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 10 e 90 por cento <br/>            do tamanho da área de plotagem).<br/>            Leitura/Gravação **int**. |
| [`bubble_size_scale`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Especifica o fator de escala para o gráfico de bolhas (pode estar <br/>            entre 0 e 300 por cento do tamanho padrão).<br/>            Leitura/Gravação **int**. |
| [`hi_low_lines_format`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Especifica o formato HiLowLines. <br/>            HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Especifica como os valores de tamanho das bolhas são representados no gráfico de bolhas.<br/>            Leitura/Gravação [`BubbleSizeRepresentationType`](/slides/python-net/pt/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Obtém o elemento no índice especificado.

## Indexador

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Observações

1) Veja o resumo e as observações para a classe ChartSeriesGroupCollection e o enum CombinableSeriesTypesGroup.
2) O grupo de séries contém algumas propriedades de séries que são comuns a 
   cada série no grupo ("propriedades do grupo de séries").
   "Propriedades do grupo de séries" na classe ChartSeriesGroup é leitura/gravação.
   Cada uma das "propriedades do grupo de séries" pode ter uma projeção somente leitura na classe ChartSeries.


### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)