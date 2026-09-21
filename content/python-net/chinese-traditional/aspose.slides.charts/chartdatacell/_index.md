---
title: ChartDataCell class
second_title: Aspose.Slides for Python via .NET API 參考手冊
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdatacell/
---
## ChartDataCell 類別

表示圖表資料的儲存格。

ChartDataCell 類型公開以下成員：

## 屬性

| Property | 說明 |
| :- | :- |
| [`row`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/row/) | 返回儲存格所在工作表行的索引。<br/>            唯讀 **int**. |
| [`column`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/column/) | 返回儲存格所在工作表列的索引。<br/>            唯讀 **int**. |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/value/) | 取得或設定儲存格的值。<br/>            讀/寫 **any**. |
| [`formula`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/formula/) | 取得或設定 A1 風格的公式。 |
| [`r1c1_formula`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/r1c1_formula/) | 取得或設定 R1C1 風格的公式。 |
| [`chart_data_worksheet`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | 取得工作表。<br/>            唯讀 [`IChartDataWorksheet`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/is_hidden/) | 判斷儲存格是否已隱藏。<br/>            唯讀 **bool**. |
| [`custom_number_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/custom_number_format/) | 取得或設定數字和日期的自訂顯示格式。<br/>            如果值為空，將使用 PresetNumberFormat 值。<br/>            讀/寫 **str**. |
| [`preset_number_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/preset_number_format/) | 取得或設定數字和日期的內建顯示格式。預設編號必須在 [0..22] 或 [37..49] 之間。<br/>            讀/寫 **int**. |

## 方法

| Method | 說明 |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell/calculate/#bool) | 如果儲存格包含公式，則會根據該公式更新其值。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)