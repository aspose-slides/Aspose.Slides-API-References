---
title: ChartDataPoint class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint classe

Representa um ponto de dados da série.

O tipo ChartDataPoint expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`x_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Somente leitura [`IStringOrDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/size_value/) | Retorna o valor de tamanho do ponto de dados do gráfico.<br/>            Usado com gráficos Treemap e Sunburst.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/color_value/) | Retorna o valor de cor do ponto de dados do gráfico.<br/>            Usado com gráficos de mapa.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Representa os valores das barras de erro da série no caso de tipo de valor Custom.<br/>            Somente leitura [`IErrorBarsCustomValues`](/slides/python-net/pt/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Somente leitura [`IDataLabel`](/slides/python-net/pt/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Especifica que as bolhas têm um efeito 3-D aplicado a elas.<br/>            Leitura/gravação **bool**. |
| [`explosion`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/explosion/) | Especifica a quantidade que o ponto de dados deve ser deslocado do centro do gráfico de pizza.<br/>            Leitura/gravação **int**. |
| [`format`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/format/) | Representa as propriedades de formatação.<br/>            Leitura/gravação [`IFormat`](/slides/python-net/pt/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/marker/) | Especifica um marcador de dados.<br/>            Somente leitura [`IMarker`](/slides/python-net/pt/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/set_as_total/) | Define o ponto de dados como total. Aplicado somente ao tipo de série Waterfall. |
| [`related_legend_entry`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico da seguinte lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Somente leitura [`ILegendEntryProperties`](/slides/python-net/pt/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/data_point_levels/) | Retorna o contêiner dos níveis de ponto de dados. Aplicado para séries Treeamp e Sunburst.<br/>            A indexação dos níveis de ponto de dados começa em zero. |
| [`index`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo.<br/>            Leitura/gravação **bool**. |
| [`cached_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/cached_value/) | Obtém o valor em cache de um ponto de dados do gráfico.<br/>            Somente leitura [`ICachedChartValue`](/slides/python-net/pt/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/cached_x_value/) | Obtém o valor X em cache de um ponto de dados do gráfico.<br/>            Somente leitura [`ICachedChartValue`](/slides/python-net/pt/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/cached_y_value/) | Obtém o valor Y em cache de um ponto de dados do gráfico.<br/>            Somente leitura [`ICachedChartValue`](/slides/python-net/pt/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Obtém o tamanho da bolha em cache de um ponto de dados do gráfico.<br/>            Somente leitura [`ICachedChartValue`](/slides/python-net/pt/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_x/) | Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter os valores reais.<br/>            Leitura **float**. |
| [`actual_y`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_y/) | Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter os valores reais.<br/>            Leitura **float**. |
| [`actual_width`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_width/) | Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais.<br/>            Leitura **float**. |
| [`actual_height`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_height/) | Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais.<br/>            Leitura **float**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`remove(self)`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/remove/#) | Remove o DataPoint da série do gráfico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Retorna uma cor automática do ponto de dados baseada no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e no estilo do gráfico.<br/>            Esta cor é usada por padrão se FillType for igual a NotDefined. |

### Ver também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)