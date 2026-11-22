---
title: ChartData class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/
---
## Clase ChartData

Representa los datos utilizados para trazar un gráfico.

El tipo ChartData expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/es/aspose.slides.charts/chartdata/chart_data_workbook/) | Obtiene la fábrica de celdas para crear celdas usadas en series o categorías de gráficos.<br/>            Solo lectura [`IChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/es/aspose.slides.charts/chartdata/series/) | Obtiene las series.<br/>            Solo lectura [`IChartSeriesCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/es/aspose.slides.charts/chartdata/series_groups/) | Obtiene los grupos de series.<br/>            Solo lectura [`IChartSeriesGroupCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories/) | Obtiene las categorías primarias (o tanto las categorías primarias como secundarias <br/>            si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es false).<br/>            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories/) | Si es false entonces la propiedad [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) devuelve None y los datos <br/>            en la propiedad [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) se utilizan tanto para series primarias como secundarias.<br/>            Si es true entonces los datos en la propiedad [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) se utilizan para series secundarias y los datos <br/>            en la propiedad [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) se utilizan para series primarias.<br/>            Lectura/escritura **bool**. |
| [`secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories/) | Obtiene las categorías secundarias si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es true.<br/>            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/es/aspose.slides.charts/chartdata/data_source_type/) | Representa la ruta del libro de trabajo externo si la fuente de datos es externa, None en caso contrario |
| [`external_workbook_path`](/slides/python-net/es/aspose.slides.charts/chartdata/external_workbook_path/) | Representa la fuente de datos del gráfico |
| [`embedded_workbook_type`](/slides/python-net/es/aspose.slides.charts/chartdata/embedded_workbook_type/) | Obtiene el tipo del libro de trabajo incrustado.<br/>            Devuelve [`WorkbookType.NOT_DEFINED`](/slides/python-net/es/aspose.slides.charts/workbooktype/NOT_DEFINED) si [`ChartData.data_source_type`](/slides/python-net/es/aspose.slides.charts/chartdata/data_source_type) es <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/es/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Solo lectura [`WorkbookType`](/slides/python-net/es/aspose.slides.charts/workbooktype). |

## Métodos

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/es/aspose.slides.charts/chartdata/set_external_workbook/#str) | Establece el libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán a partir del libro de trabajo de destino. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/es/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Establece el libro de trabajo externo como fuente de datos para el gráfico. |
| [`read_workbook_stream(self)`](/slides/python-net/es/aspose.slides.charts/chartdata/read_workbook_stream/#) | Escribe el libro de trabajo Excel interno en un flujo. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/es/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Inicializa el libro de trabajo Excel interno con un valor especificado por el usuario. |
| [`get_range(self)`](/slides/python-net/es/aspose.slides.charts/chartdata/get_range/#) | Obtiene el rango de datos del gráfico. |
| [`set_range(self, formula)`](/slides/python-net/es/aspose.slides.charts/chartdata/set_range/#str) | Establece el rango de datos del gráfico. Las series y categorías se actualizarán según el nuevo rango de datos.<br/>            Si la cantidad de series en el rango de datos es mayor que el número de series en los datos del gráfico, entonces se agregarán series adicionales con el mismo tipo<br/>            que la última serie de la colección actual al final de la colección. |
| [`refresh_data(self)`](/slides/python-net/es/aspose.slides.charts/chartdata/refresh_data/#) | Actualiza los datos del gráfico recargándolos del libro de trabajo fuente. |
| [`switch_row_column(self)`](/slides/python-net/es/aspose.slides.charts/chartdata/switch_row_column/#) | Intercambia los datos entre los ejes.<br/>            Los datos graficados en el eje X se moverán al eje Y y viceversa. |


### Véase también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)