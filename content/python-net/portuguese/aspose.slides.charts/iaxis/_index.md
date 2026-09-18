---
title: IAxis class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/iaxis/
---
## IAxis classe

Encapsula o objeto que representa o eixo de um gráfico.

O tipo IAxis expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/pt/aspose.slides.charts/iaxis/axis_between_categories/) | Representa se o eixo de valores cruza o eixo de categorias entre as categorias.<br/>            Esta propriedade se aplica apenas a eixos de categoria, e não se aplica a gráficos 3-D.<br/>            Leitura/gravação **bool**. |
| [`cross_at`](/slides/python-net/pt/aspose.slides.charts/iaxis/cross_at/) | Representa o ponto no eixo onde o eixo perpendicular o cruza.<br/>            Leitura/gravação **float**. |
| [`display_unit`](/slides/python-net/pt/aspose.slides.charts/iaxis/display_unit/) | Especifica o valor de escala das unidades de exibição para o eixo de valores.<br/>            Leitura/gravação [`DisplayUnitType`](/slides/python-net/pt/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/pt/aspose.slides.charts/iaxis/actual_max_value/) | Especifica o valor máximo real no eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real. |
| [`actual_min_value`](/slides/python-net/pt/aspose.slides.charts/iaxis/actual_min_value/) | Especifica o valor mínimo real no eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real. |
| [`actual_major_unit`](/slides/python-net/pt/aspose.slides.charts/iaxis/actual_major_unit/) | Especifica a unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real. |
| [`actual_minor_unit`](/slides/python-net/pt/aspose.slides.charts/iaxis/actual_minor_unit/) | Especifica a unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real. |
| [`actual_major_unit_scale`](/slides/python-net/pt/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Especifica a escala da unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real. |
| [`actual_minor_unit_scale`](/slides/python-net/pt/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Especifica a escala da unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real. |
| [`is_automatic_max_value`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_max_value/) | Indica se o valor máximo é atribuído automaticamente.<br/>             Leitura/gravação **bool**. |
| [`max_value`](/slides/python-net/pt/aspose.slides.charts/iaxis/max_value/) | Representa o valor máximo no eixo de valores.<br/>             Leitura/gravação **float**. |
| [`minor_unit`](/slides/python-net/pt/aspose.slides.charts/iaxis/minor_unit/) | Representa as unidades secundárias para o eixo de data ou valores.<br/>             Leitura/gravação **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Indica se a unidade secundária do eixo é atribuída automaticamente.<br/>             Leitura/gravação **bool**. |
| [`major_unit`](/slides/python-net/pt/aspose.slides.charts/iaxis/major_unit/) | Representa as unidades principais para o eixo de data ou valores.<br/>             Leitura/gravação **float**. |
| [`is_automatic_major_unit`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Indica se a unidade principal do eixo é atribuída automaticamente.<br/>            Leitura/gravação **bool**. |
| [`is_automatic_min_value`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_min_value/) | Indica se o valor mínimo é atribuído automaticamente.<br/>             Leitura/gravação **bool**. |
| [`min_value`](/slides/python-net/pt/aspose.slides.charts/iaxis/min_value/) | Representa o valor mínimo no eixo de valores.<br/>             Leitura/gravação **float**. |
| [`is_logarithmic`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_logarithmic/) | Representa se o tipo de escala do eixo de valores é logarítmico ou não.<br/>             Leitura/gravação **bool**. |
| [`log_base`](/slides/python-net/pt/aspose.slides.charts/iaxis/log_base/) | Representa a base logarítmica. O valor padrão é 10.<br/>             Leitura/gravação **float**. |
| [`is_plot_order_reversed`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Representa se o MS PowerPoint plota os pontos de dados do último para o primeiro.<br/>             Leitura/gravação **bool**. |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_visible/) | Representa se o eixo está visível.<br/>             Leitura/gravação **bool**. |
| [`major_tick_mark`](/slides/python-net/pt/aspose.slides.charts/iaxis/major_tick_mark/) | Representa o tipo de marca principal para o eixo especificado.<br/>             Leitura/gravação [`TickMarkType`](/slides/python-net/pt/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/pt/aspose.slides.charts/iaxis/minor_tick_mark/) | Representa o tipo de marca secundária para o eixo especificado.<br/>             Leitura/gravação [`TickMarkType`](/slides/python-net/pt/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/pt/aspose.slides.charts/iaxis/tick_label_position/) | Representa a posição dos rótulos das marcas no eixo especificado.<br/>             Leitura/gravação [`TickLabelPositionType`](/slides/python-net/pt/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/pt/aspose.slides.charts/iaxis/major_unit_scale/) | Representa a escala da unidade principal para o eixo de data.<br/>             Leitura/gravação [`TimeUnitType`](/slides/python-net/pt/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/pt/aspose.slides.charts/iaxis/minor_unit_scale/) | Representa a escala da unidade principal para o eixo de data.<br/>             Leitura/gravação [`TimeUnitType`](/slides/python-net/pt/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/pt/aspose.slides.charts/iaxis/base_unit_scale/) | Especifica a menor unidade de tempo representada no eixo de data.<br/>            Leitura/gravação [`TimeUnitType`](/slides/python-net/pt/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/pt/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Representa o formato das linhas de grade secundárias em um eixo de gráfico.<br/>             Somente leitura [`IChartLinesFormat`](/slides/python-net/pt/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/pt/aspose.slides.charts/iaxis/major_grid_lines_format/) | Representa o formato das linhas de grade principais em um eixo de gráfico.<br/>             Somente leitura [`IChartLinesFormat`](/slides/python-net/pt/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/pt/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Representa se as linhas de grade secundárias são exibidas.<br/>             Somente leitura **bool**. |
| [`show_major_grid_lines`](/slides/python-net/pt/aspose.slides.charts/iaxis/show_major_grid_lines/) | Representa se as linhas de grade principais são exibidas.<br/>             Somente leitura **bool**. |
| [`format`](/slides/python-net/pt/aspose.slides.charts/iaxis/format/) | Representa o formato do eixo.<br/>             Somente leitura [`IAxisFormat`](/slides/python-net/pt/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/pt/aspose.slides.charts/iaxis/title/) | Obtém o título do eixo.<br/>             Somente leitura [`IChartTitle`](/slides/python-net/pt/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/pt/aspose.slides.charts/iaxis/cross_type/) | Representa o CrossType no eixo especificado onde o outro eixo o cruza.<br/>             Leitura/gravação [`CrossesType`](/slides/python-net/pt/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/pt/aspose.slides.charts/iaxis/position/) | Representa a posição do eixo.<br/>             Leitura/gravação [`AxisPositionType`](/slides/python-net/pt/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/pt/aspose.slides.charts/iaxis/has_title/) | Determina se um eixo tem um título visível.<br/>            Leitura/gravação **bool**. |
| [`number_format`](/slides/python-net/pt/aspose.slides.charts/iaxis/number_format/) | Representa a cadeia de formato para os rótulos do eixo.<br/>            Leitura/gravação **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Indica se o formato está vinculado a dados de origem.<br/>            Leitura/gravação **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/pt/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Representa o ângulo de rotação dos rótulos das marcas<br/>            Leitura/gravação **float**. |
| [`tick_label_spacing`](/slides/python-net/pt/aspose.slides.charts/iaxis/tick_label_spacing/) | Especifica quantas etiquetas de marca devem ser puladas entre as rótulos que são desenhados.<br/>            Leitura/gravação **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Especifica o valor de espaçamento automático das etiquetas de marca. Se falso: use a propriedade TickLabelSpacing.<br/>            Leitura/gravação **bool**. |
| [`tick_marks_spacing`](/slides/python-net/pt/aspose.slides.charts/iaxis/tick_marks_spacing/) | Especifica quantas marcas de escala devem ser puladas antes da próxima ser <br/>            desenhada. Aplicado a eixos de categoria ou de série.<br/>            Leitura/gravação **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Especifica o valor de espaçamento automático das marcas de escala. Se falso: use a propriedade TickMarksSpacing.<br/>            Leitura/gravação **bool**. |
| [`label_offset`](/slides/python-net/pt/aspose.slides.charts/iaxis/label_offset/) | Especifica a distância dos rótulos ao eixo. Aplicado a eixo de categoria ou data. O valor deve estar entre 0% e 1000%.<br/>            Leitura/gravação **int**. |
| [`category_axis_type`](/slides/python-net/pt/aspose.slides.charts/iaxis/category_axis_type/) | Especifica o tipo do eixo de categoria.<br/>            Leitura/gravação [`IAxis.category_axis_type`](/slides/python-net/pt/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/pt/aspose.slides.charts/iaxis/aggregation_type/) | Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado a categoria. Usado apenas com séries Histogram ou HistogramPareto. |
| [`bin_width`](/slides/python-net/pt/aspose.slides.charts/iaxis/bin_width/) | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth.<br/>            Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto. |
| [`number_of_bins`](/slides/python-net/pt/aspose.slides.charts/iaxis/number_of_bins/) | Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins.<br/>            Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_overflow_bin/) | Especifica se o bin de estouro é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de estouro. |
| [`is_automatic_overflow_bin`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Especifica o valor automático do bin de estouro. Se falso: use a propriedade OverflowBin. |
| [`overflow_bin`](/slides/python-net/pt/aspose.slides.charts/iaxis/overflow_bin/) | Especifica o valor personalizado do bin de estouro. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e a propriedade IsOverflowBin é true. |
| [`is_underflow_bin`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_underflow_bin/) | Especifica se o bin de subfluxo é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de subfluxo. |
| [`is_automatic_underflow_bin`](/slides/python-net/pt/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Especifica o valor automático do bin de subfluxo. Se falso: use a propriedade UnderflowBin. |
| [`underflow_bin`](/slides/python-net/pt/aspose.slides.charts/iaxis/underflow_bin/) | Especifica o valor personalizado do bin de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e a propriedade IsUnderflowBin é true. |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/iaxis/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/pt/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Define a propriedade IAxis.CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo. |


### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)