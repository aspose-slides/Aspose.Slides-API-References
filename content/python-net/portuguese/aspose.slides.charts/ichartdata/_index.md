---
title: IChartData class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartdata/
---
## IChartData classe

Representa os dados usados para plotar um gráfico.

O tipo IChartData expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/pt/aspose.slides.charts/ichartdata/chart_data_workbook/) | Obtém a fábrica de células para criar células usadas para séries ou categorias do gráfico.<br/>            Somente leitura [`IChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/pt/aspose.slides.charts/ichartdata/series/) | Obtém as séries.<br/>            Somente leitura [`IChartSeriesCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/pt/aspose.slides.charts/ichartdata/series_groups/) | Obtém os grupos de séries.<br/>            Somente leitura [`IChartSeriesGroupCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories/) | Obtém as categorias primárias (ou tanto as categorias primárias quanto as secundárias <br/>            se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for falsa).<br/>            Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories/) | Se false então a propriedade [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) retorna None e os dados <br/>            na propriedade [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) são usados tanto para séries primárias quanto para séries secundárias.<br/>            Se true então os dados na propriedade [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) são usados para séries secundárias e os dados <br/>            na propriedade [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) são usados para séries primárias.<br/>            Leitura/gravação **bool**. |
| [`secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories/) | Obtém as categorias secundárias se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for true.<br/>            Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/pt/aspose.slides.charts/ichartdata/data_source_type/) | Representa a fonte de dados do gráfico |
| [`external_workbook_path`](/slides/python-net/pt/aspose.slides.charts/ichartdata/external_workbook_path/) | Representa o caminho do workbook externo se a fonte de dados for externa, caso contrário None |
| [`embedded_workbook_type`](/slides/python-net/pt/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Obtém o tipo do workbook incorporado.<br/>            Retorna [`WorkbookType.NOT_DEFINED`](/slides/python-net/pt/aspose.slides.charts/workbooktype/NOT_DEFINED) se [`IChartData.data_source_type`](/slides/python-net/pt/aspose.slides.charts/ichartdata/data_source_type) for <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pt/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Somente leitura [`WorkbookType`](/slides/python-net/pt/aspose.slides.charts/workbooktype). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/pt/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Define o workbook externo como fonte de dados para o gráfico. Os dados do gráfico serão atualizados a partir do workbook de destino. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/pt/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Define o workbook externo como fonte de dados para o gráfico. |
| [`read_workbook_stream(self)`](/slides/python-net/pt/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Grava o workbook Excel interno em um fluxo na memória. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/pt/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Inicializa o workbook Excel interno com o valor especificado pelo usuário. |
| [`set_range(self, formula)`](/slides/python-net/pt/aspose.slides.charts/ichartdata/set_range/#str) | Define o intervalo de dados do gráfico. As séries e categorias serão atualizadas com base no novo intervalo de dados.<br/>            Se a quantidade de séries no intervalo de dados for maior que a contagem de séries nos dados do gráfico, então séries adicionais com o mesmo tipo<br/>            da última série na coleção atual serão adicionadas ao final da coleção. |
| [`get_range(self)`](/slides/python-net/pt/aspose.slides.charts/ichartdata/get_range/#) | Obtém o intervalo de dados do gráfico. |
| [`switch_row_column(self)`](/slides/python-net/pt/aspose.slides.charts/ichartdata/switch_row_column/#) | Troca os dados entre os eixos.<br/>            Dados plotados no eixo X serão movidos para o eixo Y e vice-versa. |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)