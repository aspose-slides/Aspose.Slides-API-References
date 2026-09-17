---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/
---
## IChartData 类

表示用于图表绘制的数据。

IChartData 类型公开以下成员：

## 属性

| 属性 | 说明 |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/zh/aspose.slides.charts/ichartdata/chart_data_workbook/) | 获取用于创建用于图表系列或类别的单元格的工厂。<br/>            只读 [`IChartDataWorkbook`](/slides/python-net/zh/aspose.slides.charts/ichartdataworkbook)。 |
| [`series`](/slides/python-net/zh/aspose.slides.charts/ichartdata/series/) | 获取系列。<br/>            只读 [`IChartSeriesCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriescollection)。 |
| [`series_groups`](/slides/python-net/zh/aspose.slides.charts/ichartdata/series_groups/) | 获取系列的分组。<br/>            只读 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)。 |
| [`categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories/) | 获取主类别（如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 false，则获取主类别和次要类别）。<br/>            只读 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)。 |
| [`use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories/) | 如果为 false，则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 属性返回 None，且 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据同时用于主系列和次要系列。<br/>            如果为 true，则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 属性中的数据用于次要系列，[`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据用于主系列。<br/>            读/写 **bool**。 |
| [`secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories/) | 如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 true，则获取次要类别。<br/>            只读 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)。 |
| [`data_source_type`](/slides/python-net/zh/aspose.slides.charts/ichartdata/data_source_type/) | 表示图表的数据源 |
| [`external_workbook_path`](/slides/python-net/zh/aspose.slides.charts/ichartdata/external_workbook_path/) | 如果数据源是外部的，则表示外部工作簿路径；否则为 None |
| [`embedded_workbook_type`](/slides/python-net/zh/aspose.slides.charts/ichartdata/embedded_workbook_type/) | 获取嵌入式工作簿的类型。<br/>            如果 [`IChartData.data_source_type`](/slides/python-net/zh/aspose.slides.charts/ichartdata/data_source_type) 为 <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/zh/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK)，则返回 [`WorkbookType.NOT_DEFINED`](/slides/python-net/zh/aspose.slides.charts/workbooktype/NOT_DEFINED)。<br/>            只读 [`WorkbookType`](/slides/python-net/zh/aspose.slides.charts/workbooktype)。 |

## 方法

| 方法 | 说明 |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/zh/aspose.slides.charts/ichartdata/set_external_workbook/#str) | 将外部工作簿设置为图表的数据源。图表数据将从目标工作簿更新。 |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/zh/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | 将外部工作簿设置为图表的数据源。 |
| [`read_workbook_stream(self)`](/slides/python-net/zh/aspose.slides.charts/ichartdata/read_workbook_stream/#) | 将内部包含的 Excel 工作簿写入内存流。 |
| [`write_workbook_stream(self, ms)`](/slides/python-net/zh/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | 使用用户指定的值初始化内部包含的 Excel 工作簿。 |
| [`set_range(self, formula)`](/slides/python-net/zh/aspose.slides.charts/ichartdata/set_range/#str) | 设置图表数据范围。系列和类别将基于新的数据范围进行更新。<br/>            如果数据范围中的系列数量大于图表数据中的系列计数，则会在当前集合的末尾添加具有与最后一个系列相同类型的附加系列。 |
| [`get_range(self)`](/slides/python-net/zh/aspose.slides.charts/ichartdata/get_range/#) | 获取图表数据范围。 |
| [`switch_row_column(self)`](/slides/python-net/zh/aspose.slides.charts/ichartdata/switch_row_column/#) | 交换轴上的数据。<br/>            在 X 轴上绘制的数据将移动到 Y 轴，反之亦然。 |


### 另请参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)