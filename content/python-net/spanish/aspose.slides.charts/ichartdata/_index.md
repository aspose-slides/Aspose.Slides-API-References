---
title: IChartData class
second_title: Aspose.Slides para Python a través de la referencia de API de .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/
---
## IChartData clase

Representa los datos usados para graficar un gráfico.

El tipo IChartData expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/es/aspose.slides.charts/ichartdata/chart_data_workbook/) | Obtiene la fábrica de celdas para crear celdas usadas en series o categorías del gráfico.<br/>            Solo lectura [`IChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/es/aspose.slides.charts/ichartdata/series/) | Obtiene las series.<br/>            Solo lectura [`IChartSeriesCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/es/aspose.slides.charts/ichartdata/series_groups/) | Obtiene los grupos de series.<br/>            Solo lectura [`IChartSeriesGroupCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories/) | Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias <br/>            si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es false).<br/>            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories/) | Si false entonces la propiedad [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) devuelve None y los datos <br/>            en la propiedad [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) se usan tanto para series primarias como secundarias.<br/>            Si true entonces los datos en la propiedad [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) se usan para series secundarias y los datos <br/>            en la propiedad [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) se usan para series primarias.<br/>            Lectura/escritura **bool**. |
| [`secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories/) | Obtiene las categorías secundarias si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es true.<br/>            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/es/aspose.slides.charts/ichartdata/data_source_type/) | Representa la fuente de datos del gráfico |
| [`external_workbook_path`](/slides/python-net/es/aspose.slides.charts/ichartdata/external_workbook_path/) | Representa la ruta al libro de trabajo externo si la fuente de datos es externa, None en caso contrario |
| [`embedded_workbook_type`](/slides/python-net/es/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Obtiene el tipo del libro de trabajo incrustado.<br/>            Devuelve [`WorkbookType.NOT_DEFINED`](/slides/python-net/es/aspose.slides.charts/workbooktype/NOT_DEFINED) si [`IChartData.data_source_type`](/slides/python-net/es/aspose.slides.charts/ichartdata/data_source_type) es <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/es/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Solo lectura [`WorkbookType`](/slides/python-net/es/aspose.slides.charts/workbooktype). |

## Métodos

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/es/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Establece un libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de trabajo de destino. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/es/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Establece un libro de trabajo externo como fuente de datos para el gráfico. |
| [`read_workbook_stream(self)`](/slides/python-net/es/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Escribe el libro de trabajo Excel contenido internamente en un flujo en memoria. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/es/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Inicializa el libro de trabajo Excel contenido internamente con el valor especificado por el usuario. |
| [`set_range(self, formula)`](/slides/python-net/es/aspose.slides.charts/ichartdata/set_range/#str) | Establece el rango de datos del gráfico. Las series y categorías se actualizarán según el nuevo rango de datos.<br/>            Si la cantidad de series en el rango de datos es mayor que el recuento de series en los datos del gráfico, se añadirán series adicionales del mismo tipo<br/>            que la última serie de la colección actual al final de la colección. |
| [`get_range(self)`](/slides/python-net/es/aspose.slides.charts/ichartdata/get_range/#) | Obtiene el rango de datos del gráfico. |
| [`switch_row_column(self)`](/slides/python-net/es/aspose.slides.charts/ichartdata/switch_row_column/#) | Intercambia los datos entre los ejes.<br/>            Los datos graficados en el eje X se moverán al eje Y y viceversa. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)