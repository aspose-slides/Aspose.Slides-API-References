---
title: ChartSeriesGroup class
second_title: Referência da API Aspose.Slides for Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Representa um grupo de séries.

O tipo ChartSeriesGroup expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/type/) | Retorna um tipo deste grupo de séries.<br/>            Somente leitura [`CombinableSeriesTypesGroup`](/slides/python-net/pt/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indica se as séries deste grupo são plotadas em eixo secundário.<br/>            Somente leitura **bool**. |
| [`series`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/series/) | Retorna uma coleção de séries.<br/>            Somente leitura [`IChartSeriesReadonlyCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Fornece acesso às barras alta/baixa de gráficos de linha ou de ações.<br/>            Somente leitura [`IUpDownBarsManager`](/slides/python-net/pt/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/gap_width/) | Obtém ou define o espaço entre agrupamentos de barras ou colunas, como porcentagem da largura da barra ou coluna.<br/>            O valor deve estar entre 0 e 500.<br/>            Leitura/gravação **int**. |
| [`gap_depth`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/gap_depth/) | Obtém ou define a distância entre séries de dados em um gráfico 3D, como porcentagem da largura do marcador.<br/>            O valor deve estar entre 0 e 500.<br/>            Leitura/gravação **int**. |
| [`first_slice_angle`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Obtém ou define o ângulo do primeiro segmento de pizza ou rosca, <br/>            em graus (no sentido horário a partir de cima, de 0 a 360 graus).<br/>            Leitura/gravação **int**. |
| [`doughnut_hole_size`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 0 e 90% <br/>            do tamanho da área de plotagem).<br/>            Leitura/gravação **int**. |
| [`overlap`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/overlap/) | Especifica o quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%).<br/>             - -100%: Espaçamento máximo (barras completamente separadas).<br/>             - 0%: Barras posicionadas lado a lado sem sobreposição ou espaçamento.<br/>             - 100%: Sobreposição máxima (barras totalmente sobrepostas).<br/>             Esta propriedade é leitura/gravação **int**. |
| [`second_pie_size`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Especifica o tamanho da segunda fatia de pizza ou barra em um gráfico de pizza-em-pizza ou <br/>            barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode <br/>            estar entre 5 e 200%).<br/>            Leitura/gravação **int**. |
| [`bubble_size_representation`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Especifica como os valores de tamanho das bolhas são representados no gráfico de bolhas.<br/>            Leitura/gravação [`BubbleSizeRepresentationType`](/slides/python-net/pt/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Especifica um valor que será usado para determinar quais pontos de dados <br/>            estão na segunda pizza ou barra em um gráfico de pizza-em-pizza ou barra-em-pizza. <br/>            É usado em conjunto com a propriedade PieSplitBy.<br/>            Leitura/gravação **float**. |
| [`pie_split_by`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra <br/>            em um gráfico de pizza-em-pizza ou barra-em-pizza.<br/>            Leitura/gravação [`PieSplitType`](/slides/python-net/pt/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Especifica que cada marcador de dados na série tem uma cor diferente.<br/>            Leitura/gravação **bool**. |
| [`has_series_lines`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barras empilhadas e OfPie.<br/>            Leitura/gravação **bool**. |
| [`hi_low_lines_format`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Especifica o formato HiLowLines. <br/>            HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Especifica o fator de escala para o gráfico de bolhas (pode estar <br/>            entre 0 e 300% do tamanho padrão).<br/>            Leitura/gravação **int**. |
| [`pie_split_custom_points`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | As informações de divisão personalizada para um gráfico de pizza-em-pizza ou barra-em-pizza com divisão personalizada.<br/>            Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico de pizza-em-pizza ou <br/>            barra-em-pizza.<br/>            Somente leitura [`PieSplitCustomPointCollection`](/slides/python-net/pt/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/chart/) | Retorna o gráfico pai.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Obtém o elemento no índice especificado.

## Indexador

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Observações

1) Veja o resumo e observações da classe ChartSeriesGroupCollection e do enum CombinableSeriesTypesGroup.  
2) O grupo de séries contém algumas propriedades de série que são comuns a  
cada série no grupo ("propriedades do grupo de séries").  
As "propriedades do grupo de séries" na classe ChartSeriesGroup são leitura/gravação.  
Cada uma das "propriedades do grupo de séries" pode ter uma projeção somente leitura na classe ChartSeries.  

### Consulte também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)