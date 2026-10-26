---
title: ChartData class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/
---
## ChartData classe

Representa os dados usados para a plotagem de um gráfico.

O tipo ChartData expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/pt/aspose.slides.charts/chartdata/chart_data_workbook/) | Obtém a fábrica de células para criar células usadas em séries ou categorias do gráfico.<br/>            Somente leitura [`IChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/pt/aspose.slides.charts/chartdata/series/) | Obtém as séries.<br/>            Somente leitura [`IChartSeriesCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/pt/aspose.slides.charts/chartdata/series_groups/) | Obtém os grupos de séries.<br/>            Somente leitura [`IChartSeriesGroupCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories/) | Obtém as categorias principais (ou tanto as categorias principais quanto as secundárias <br/>            se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for falsa).<br/>            Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories/) | Se for false, a propriedade [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) retornará None e os dados <br/>            na propriedade [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) serão usados tanto para séries principais quanto para séries secundárias.<br/>            Se for true, os dados na propriedade [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) serão usados para séries secundárias e os dados <br/>            na propriedade [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) serão usados para séries principais.<br/>            Leitura/Gravação **bool**. |
| [`secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories/) | Obtém as categorias secundárias se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for true.<br/>            Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/pt/aspose.slides.charts/chartdata/data_source_type/) | Representa o caminho do workbook externo se houver fonte de dados externa, caso contrário None |
| [`external_workbook_path`](/slides/python-net/pt/aspose.slides.charts/chartdata/external_workbook_path/) | Representa a fonte de dados do gráfico |
| [`embedded_workbook_type`](/slides/python-net/pt/aspose.slides.charts/chartdata/embedded_workbook_type/) | Obtém o tipo do workbook incorporado.<br/>            Retorna [`WorkbookType.NOT_DEFINED`](/slides/python-net/pt/aspose.slides.charts/workbooktype/NOT_DEFINED) se [`ChartData.data_source_type`](/slides/python-net/pt/aspose.slides.charts/chartdata/data_source_type) for <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pt/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Somente leitura [`WorkbookType`](/slides/python-net/pt/aspose.slides.charts/workbooktype). |

## Métodos

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/pt/aspose.slides.charts/chartdata/set_external_workbook/#str) | Define o workbook externo como fonte de dados para o gráfico. Os dados do gráfico serão atualizados a partir do workbook de destino. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/pt/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Define o workbook externo como fonte de dados para o gráfico. |
| [`read_workbook_stream(self)`](/slides/python-net/pt/aspose.slides.charts/chartdata/read_workbook_stream/#) | Grava o workbook Excel contido internamente em um fluxo. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/pt/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Inicializa o workbook Excel contido internamente com o valor especificado pelo usuário. |
| [`get_range(self)`](/slides/python-net/pt/aspose.slides.charts/chartdata/get_range/#) | Obtém o intervalo de dados do gráfico. |
| [`set_range(self, formula)`](/slides/python-net/pt/aspose.slides.charts/chartdata/set_range/#str) | Define o intervalo de dados do gráfico. As séries e categorias serão atualizadas com base no novo intervalo de dados.<br/>            Se a quantidade de séries no intervalo de dados for maior que a contagem de séries nos dados do gráfico, então séries adicionais com o mesmo tipo<br/>            da última série na coleção atual serão adicionadas ao final da coleção. |
| [`switch_row_column(self)`](/slides/python-net/pt/aspose.slides.charts/chartdata/switch_row_column/#) | Troca os dados ao longo do eixo.<br/>            Dados plotados no eixo X serão movidos para o eixo Y e vice-versa. |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)