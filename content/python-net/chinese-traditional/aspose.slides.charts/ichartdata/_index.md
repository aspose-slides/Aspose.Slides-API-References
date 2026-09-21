---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/
---
## IChartData 類別

代表用於圖表繪製的資料。

IChartData 型別公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/chart_data_workbook/) | 取得用於建立圖表系列或類別之儲存格的工廠。<br/>            唯讀 [`IChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdataworkbook)。 |
| [`series`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/series/) | 取得系列。<br/>            唯讀 [`IChartSeriesCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriescollection)。 |
| [`series_groups`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/series_groups/) | 取得系列的群組。<br/>            唯讀 [`IChartSeriesGroupCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection)。 |
| [`categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories/) | 取得主要類別（或同時取得主要與次要類別 <br/>            若 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性為 false 時）。<br/>            唯讀 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)。 |
| [`use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories/) | 若為 false，則 [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) 屬性返回 None，且 [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) 屬性中的資料同時用於主要與次要系列。<br/>            若為 true，則 [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) 屬性中的資料用於次要系列，且 [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) 屬性中的資料用於主要系列。<br/>            讀寫 **bool**。 |
| [`secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories/) | 若 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性為 true，則取得次要類別。<br/>            唯讀 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)。 |
| [`data_source_type`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/data_source_type/) | 代表圖表的資料來源 |
| [`external_workbook_path`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/external_workbook_path/) | 若資料來源是外部，則代表外部工作簿路徑；否則為 None |
| [`embedded_workbook_type`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/embedded_workbook_type/) | 取得嵌入式工作簿的類型。<br/>            若 [`IChartData.data_source_type`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/data_source_type) 為 <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK)，則返回 [`WorkbookType.NOT_DEFINED`](/slides/python-net/zh-hant/aspose.slides.charts/workbooktype/NOT_DEFINED)。<br/>            唯讀 [`WorkbookType`](/slides/python-net/zh-hant/aspose.slides.charts/workbooktype)。 |

## 方法

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/set_external_workbook/#str) | 設定外部工作簿為圖表的資料來源。圖表資料將從目標工作簿更新。 |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | 設定外部工作簿為圖表的資料來源。 |
| [`read_workbook_stream(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/read_workbook_stream/#) | 將內部包含的 Excel 工作簿寫入記憶體串流。 |
| [`write_workbook_stream(self, ms)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | 使用使用者指定的值初始化內部包含的 Excel 工作簿。 |
| [`set_range(self, formula)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/set_range/#str) | 設定圖表資料範圍。系列與類別將根據新的資料範圍更新。<br/>            若資料範圍中的系列數量大於圖表資料中的系列數量，則會在集合末端加入與目前最後一個系列具有相同類型的額外系列。 |
| [`get_range(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/get_range/#) | 取得圖表資料範圍。 |
| [`switch_row_column(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/switch_row_column/#) | 交換軸向上的資料。<br/>            繪製於 X 軸的資料將移至 Y 軸，反之亦然。 |


### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)