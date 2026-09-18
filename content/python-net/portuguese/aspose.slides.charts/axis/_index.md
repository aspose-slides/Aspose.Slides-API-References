---
title: Axis class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/axis/
---
## classe Axis

Encapsula o objeto que representa o eixo de um gráfico.

O tipo Axis expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/axis/chart/) | Retorna o gráfico pai.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/pt/aspose.slides.charts/axis/axis_between_categories/) | Representa se o eixo de valores cruza o eixo de categoria entre categorias.<br/>             Esta propriedade se aplica apenas a eixos de categoria e não se aplica a gráficos 3-D.<br/>             Leitura/gravação **bool**. |
| [`category_axis_type`](/slides/python-net/pt/aspose.slides.charts/axis/category_axis_type/) | Especifica o tipo do eixo de categoria.<br/>            Leitura/gravação [`CategoryAxisType`](/slides/python-net/pt/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/pt/aspose.slides.charts/axis/cross_at/) | Representa o ponto no eixo onde o eixo perpendicular o cruza.<br/>             Leitura/gravação **float**. |
| [`display_unit`](/slides/python-net/pt/aspose.slides.charts/axis/display_unit/) | Especifica o valor de escala das unidades de exibição para o eixo de valores.<br/>             Leitura/gravação [`DisplayUnitType`](/slides/python-net/pt/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/pt/aspose.slides.charts/axis/actual_max_value/) | Especifica o valor máximo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [`actual_min_value`](/slides/python-net/pt/aspose.slides.charts/axis/actual_min_value/) | Especifica o valor mínimo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [`actual_major_unit`](/slides/python-net/pt/aspose.slides.charts/axis/actual_major_unit/) | Especifica a unidade maior real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [`actual_minor_unit`](/slides/python-net/pt/aspose.slides.charts/axis/actual_minor_unit/) | Especifica a unidade menor real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [`actual_major_unit_scale`](/slides/python-net/pt/aspose.slides.charts/axis/actual_major_unit_scale/) | Especifica a escala da unidade maior real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [`actual_minor_unit_scale`](/slides/python-net/pt/aspose.slides.charts/axis/actual_minor_unit_scale/) | Especifica a escala da unidade menor real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real. |
| [`is_automatic_max_value`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_max_value/) | Indica se o valor máximo é atribuído automaticamente.<br/>             Leitura/gravação **bool**. |
| [`max_value`](/slides/python-net/pt/aspose.slides.charts/axis/max_value/) | Representa o valor máximo no eixo de valores.<br/>             Leitura/gravação **float**. |
| [`minor_unit`](/slides/python-net/pt/aspose.slides.charts/axis/minor_unit/) | Representa as unidades menores para o eixo de data ou de valores.<br/>             Leitura/gravação **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_minor_unit/) | Indica se a unidade menor do eixo é atribuída automaticamente.<br/>             Leitura/gravação **bool**. |
| [`major_unit`](/slides/python-net/pt/aspose.slides.charts/axis/major_unit/) | Representa as unidades maiores para o eixo de data ou de valores.<br/>             Leitura/gravação **float**. |
| [`is_automatic_major_unit`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_major_unit/) | Indica se a unidade maior do eixo é atribuída automaticamente.<br/>            Leitura/gravação **bool**. |
| [`is_automatic_min_value`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_min_value/) | Indica se o valor mínimo é atribuído automaticamente.<br/>             Leitura/gravação **bool**. |
| [`min_value`](/slides/python-net/pt/aspose.slides.charts/axis/min_value/) | Representa o valor mínimo no eixo de valores.<br/>             Leitura/gravação **float**. |
| [`is_logarithmic`](/slides/python-net/pt/aspose.slides.charts/axis/is_logarithmic/) | Representa se o tipo de escala do eixo de valores é logarítmico ou não.<br/>             Leitura/gravação **bool**. |
| [`log_base`](/slides/python-net/pt/aspose.slides.charts/axis/log_base/) | Representa a base logarítmica. O valor padrão é 10.<br/>             Leitura/gravação **float**. |
| [`is_plot_order_reversed`](/slides/python-net/pt/aspose.slides.charts/axis/is_plot_order_reversed/) | Representa se o MS PowerPoint plota os pontos de dados do último para o primeiro.<br/>             Leitura/gravação **bool**. |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/axis/is_visible/) | Representa se o eixo está visível.<br/>             Leitura/gravação **bool**. |
| [`major_tick_mark`](/slides/python-net/pt/aspose.slides.charts/axis/major_tick_mark/) | Representa o tipo de marca de graduação maior para o eixo especificado.<br/>             Leitura/gravação [`TickMarkType`](/slides/python-net/pt/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/pt/aspose.slides.charts/axis/minor_tick_mark/) | Representa o tipo de marca de graduação menor para o eixo especificado.<br/>             Leitura/gravação [`TickMarkType`](/slides/python-net/pt/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/pt/aspose.slides.charts/axis/tick_label_position/) | Representa a posição dos rótulos de marca de graduação no eixo especificado.<br/>             Leitura/gravação [`TickLabelPositionType`](/slides/python-net/pt/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/pt/aspose.slides.charts/axis/major_unit_scale/) | Representa a escala da unidade maior para o eixo de data.<br/>             Leitura/gravação [`TimeUnitType`](/slides/python-net/pt/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/pt/aspose.slides.charts/axis/minor_unit_scale/) | Representa a escala da unidade maior para o eixo de data.<br/>             Leitura/gravação [`TimeUnitType`](/slides/python-net/pt/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/pt/aspose.slides.charts/axis/base_unit_scale/) | Especifica a menor unidade de tempo representada no eixo de data.<br/>            Leitura/gravação [`TimeUnitType`](/slides/python-net/pt/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/pt/aspose.slides.charts/axis/minor_grid_lines_format/) | Representa o formato das linhas de grade menores em um eixo de gráfico.<br/>             Somente leitura [`IChartLinesFormat`](/slides/python-net/pt/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/pt/aspose.slides.charts/axis/major_grid_lines_format/) | Representa o formato das linhas de grade maiores em um eixo de gráfico.<br/>             Somente leitura [`IChartLinesFormat`](/slides/python-net/pt/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/pt/aspose.slides.charts/axis/show_minor_grid_lines/) | Para ocultar a linha de grade menor, defina MinorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill.<br/>            Somente leitura **bool**. |
| [`show_major_grid_lines`](/slides/python-net/pt/aspose.slides.charts/axis/show_major_grid_lines/) | Para ocultar a linha de grade maior, defina MajorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill.<br/>            Somente leitura **bool**. |
| [`format`](/slides/python-net/pt/aspose.slides.charts/axis/format/) | Representa o formato do eixo.<br/>             Somente leitura [`IAxisFormat`](/slides/python-net/pt/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/axis/text_format/) | Representa o formato do texto.<br/>             Somente leitura [`IChartTextFormat`](/slides/python-net/pt/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/pt/aspose.slides.charts/axis/title/) | Obtém o título do eixo.<br/>             Somente leitura [`IChartTitle`](/slides/python-net/pt/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/pt/aspose.slides.charts/axis/cross_type/) | Representa o CrossType no eixo especificado onde o outro eixo o cruza.<br/>             Leitura/gravação [`CrossesType`](/slides/python-net/pt/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/pt/aspose.slides.charts/axis/position/) | Representa a posição do eixo.<br/>             Leitura/gravação [`AxisPositionType`](/slides/python-net/pt/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/pt/aspose.slides.charts/axis/has_title/) | Determina se um eixo tem um título visível.<br/>            Leitura/gravação **bool**. |
| [`number_format`](/slides/python-net/pt/aspose.slides.charts/axis/number_format/) | Representa a string de formato para os rótulos do eixo.<br/>            Leitura/gravação **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/pt/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Indica se o formato está vinculado aos dados de origem.<br/>            Leitura/gravação **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/pt/aspose.slides.charts/axis/tick_label_rotation_angle/) | Representa o ângulo de rotação dos rótulos de graduação.<br/>            Leitura/gravação **float**. |
| [`tick_label_spacing`](/slides/python-net/pt/aspose.slides.charts/axis/tick_label_spacing/) | Especifica quantos rótulos de graduação pular entre os rótulos que são desenhados. Aplicado ao eixo de categoria ou de série.<br/>            Leitura/gravação **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Especifica o valor de espaçamento automático de rótulos de graduação. Se falso: use a propriedade TickLabelSpacing.<br/>            Leitura/gravação **bool**. |
| [`tick_marks_spacing`](/slides/python-net/pt/aspose.slides.charts/axis/tick_marks_spacing/) | Especifica quantas marcas de graduação devem ser puladas antes que a próxima seja<br/>            desenhada. Aplicado ao eixo de categoria ou de série.<br/>            Leitura/gravação **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Especifica o valor de espaçamento automático de marcas de graduação. Se falso: use a propriedade TickMarksSpacing.<br/>            Leitura/gravação **bool**. |
| [`label_offset`](/slides/python-net/pt/aspose.slides.charts/axis/label_offset/) | Especifica a distância dos rótulos do eixo. Aplicado ao eixo de categoria ou de data. O valor deve estar entre 0% e 1000%.<br/>            Leitura/gravação **int**. |
| [`aggregation_type`](/slides/python-net/pt/aspose.slides.charts/axis/aggregation_type/) | Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado a categoria. Usado somente com séries Histogram ou HistogramPareto. |
| [`bin_width`](/slides/python-net/pt/aspose.slides.charts/axis/bin_width/) | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth.<br/>            Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto. |
| [`number_of_bins`](/slides/python-net/pt/aspose.slides.charts/axis/number_of_bins/) | Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins.<br/>            Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/pt/aspose.slides.charts/axis/is_overflow_bin/) | Especifica se o bin de overflow é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de overflow. |
| [`is_automatic_overflow_bin`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Especifica o valor automático do bin de overflow. Se falso: use a propriedade OverflowBin. |
| [`overflow_bin`](/slides/python-net/pt/aspose.slides.charts/axis/overflow_bin/) | Especifica o valor personalizado do bin de overflow. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e a propriedade IsOverflowBin é true. |
| [`is_underflow_bin`](/slides/python-net/pt/aspose.slides.charts/axis/is_underflow_bin/) | Especifica se o bin de underflow é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de underflow. |
| [`is_automatic_underflow_bin`](/slides/python-net/pt/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Especifica o valor automático do bin de underflow. Se falso: use a propriedade UnderflowBin. |
| [`underflow_bin`](/slides/python-net/pt/aspose.slides.charts/axis/underflow_bin/) | Especifica o valor personalizado do bin de underflow. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e a propriedade IsUnderflowBin é true. |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/axis/presentation/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/pt/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Define a propriedade IAxis.CategoryAxisType com um valor que é determinado automaticamente com base nos dados do eixo. |

### Ver também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)