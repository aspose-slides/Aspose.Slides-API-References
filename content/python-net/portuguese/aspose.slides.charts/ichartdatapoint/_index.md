---
title: IChartDataPoint class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint classe

Representa ponto de dados da série.

O tipo IChartDataPoint expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`x_value`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/x_value/) | Retorna o valor x do ponto de dados do gráfico.<br/>            Somente leitura [`IStringOrDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/y_value/) | Retorna o valor y do ponto de dados do gráfico.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/bubble_size/) | Retorna o tamanho da bolha do ponto de dados do gráfico.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/value/) | Retorna o valor do ponto de dados do gráfico.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/size_value/) | Retorna o valor de tamanho do ponto de dados do gráfico.<br/>            Usado com gráficos Treemap e Sunburst. <br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/color_value/) | Retorna o valor de cor do ponto de dados do gráfico.<br/>            Usado com gráficos Map. <br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Representa valores de barras de erro da série no caso de tipo de valor Custom.<br/>            Somente leitura [`IErrorBarsCustomValues`](/slides/python-net/pt/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/label/) | Representa o rótulo do ponto de dados do gráfico.<br/>            Somente leitura [`IDataLabel`](/slides/python-net/pt/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Especifica que as bolhas têm um efeito 3-D aplicado a elas.<br/>            Leitura/gravação **bool**. |
| [`explosion`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/explosion/) | Especifica a quantidade que o ponto de dados deve ser movido a partir do centro da pizza.<br/>            Leitura/gravação **int**. |
| [`format`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/format/) | Representa as propriedades de formatação.<br/>            Leitura/gravação [`IFormat`](/slides/python-net/pt/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/marker/) | Especifica um marcador de dados.<br/>            Somente leitura [`IMarker`](/slides/python-net/pt/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico desta lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Somente leitura [`ILegendEntryProperties`](/slides/python-net/pt/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/set_as_total/) | Define o ponto de dados como total. Aplicado somente para o tipo de série Waterfall. |
| [`invert_if_negative`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo.<br/>            Leitura/gravação **bool**. |
| [`data_point_levels`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Retorna o contêiner dos níveis do ponto de dados. Aplicado para séries Treeamp e Sunburst.<br/>            A indexação dos níveis do ponto de dados começa em zero. |
| [`index`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/index/) | Determina a qual coleção de filhos do pai este ponto de dados se aplica.<br/>            Leitura **int**. |
| [`actual_x`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`remove(self)`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/remove/#) | Remove DataPoint da série do gráfico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Retorna uma cor automática do ponto de dados baseada no índice da série, índice do ponto de dados, na propriedade ParentSeriesGroup.IsColorVaried e no estilo do gráfico. <br/>            Esta cor é usada por padrão se FillType for igual a NotDefined. |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)