---
title: ChartDataPoint class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint classe

Representa o ponto de dados da série.

O tipo ChartDataPoint expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Somente leitura [`IStringOrDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/size_value/) | Retorna o valor de tamanho do ponto de dados do gráfico.<br/>            Usado com gráficos Treemap e Sunburst. <br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/color_value/) | Retorna o valor de cor do ponto de dados do gráfico.<br/>            Usado com gráficos Map. <br/>            Somente leitura [`IDoubleChartValue`](/slides/python-net/pt/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Representa os valores das barras de erro da série no caso do tipo de valor Custom.<br/>            Somente leitura [`IErrorBarsCustomValues`](/slides/python-net/pt/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/label/) | Rótulo.<br/>            Somente leitura [`IDataLabel`](/slides/python-net/pt/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Especifica que as bolhas têm um efeito 3-D aplicado a elas.<br/>            Leitura/gravação **bool**. |
| [`explosion`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/explosion/) | Especifica a quantidade que o ponto de dados deve ser movido a partir do centro da pizza.<br/>            Leitura/gravação **int**. |
| [`format`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/format/) | Representa as propriedades de formatação.<br/>            Leitura/gravação [`IFormat`](/slides/python-net/pt/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/marker/) | Especifica um marcador de dados.<br/>            Somente leitura [`IMarker`](/slides/python-net/pt/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/set_as_total/) | Define o ponto de dados como total. Aplicado apenas para o tipo de série Waterfall. |
| [`related_legend_entry`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico desta lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Somente leitura [`ILegendEntryProperties`](/slides/python-net/pt/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/data_point_levels/) | Retorna o contêiner dos níveis do ponto de dados. Aplicado para séries Treeamp e Sunburst.<br/>            A indexação dos níveis do ponto de dados começa em zero. |
| [`index`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo.<br/>            Leitura/gravação **bool**. |
| [`actual_x`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_x/) | Especifica a localização real x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. <br/>            Somente leitura **float**. |
| [`actual_y`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_y/) | Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. <br/>            Somente leitura **float**. |
| [`actual_width`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_width/) | Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. <br/>            Somente leitura **float**. |
| [`actual_height`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/actual_height/) | Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. <br/>            Somente leitura **float**. |

## Métodos

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/remove/#) | Remove DataPoint da série do gráfico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/pt/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Retorna uma cor automática do ponto de dados com base no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e no estilo do gráfico.<br/>            Esta cor é usada por padrão se FillType for igual a NotDefined. |

### Ver também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)