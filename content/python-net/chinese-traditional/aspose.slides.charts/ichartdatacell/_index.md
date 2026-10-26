---
title: IChartDataCell class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell 類別

表示圖表資料的儲存格。

IChartDataCell 類別公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`row`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/row/) | 返回工作表中儲存格所在列的索引。<br/>唯讀 **int**。 |
| [`column`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/column/) | 返回工作表中儲存格所在欄的索引。<br/>唯讀 **int**。 |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/value/) | 取得或設定儲存格的值。<br/>可讀寫 **any**。 |
| [`formula`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/formula/) | 取得或設定 A1 風格的公式。 |
| [`r1c1_formula`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/r1c1_formula/) | 取得或設定 R1C1 風格的公式。 |
| [`chart_data_worksheet`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | 取得工作表。<br/>唯讀 [`IChartDataWorksheet`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdataworksheet)。 |
| [`is_hidden`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/is_hidden/) | 判斷儲存格是否已隱藏。<br/>唯讀 **bool**。 |
| [`custom_number_format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/custom_number_format/) | 取得或設定數字與日期的自訂顯示格式。<br/>若值為空，將使用 PresetNumberFormat 值。<br/>可讀寫 **str**。 |
| [`preset_number_format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/preset_number_format/) | 取得或設定數字與日期的內建顯示格式。預設編號必須在 [0..22] 或 [37..49] 之間。<br/>可讀寫 **int**。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell/calculate/#bool) | 如果儲存格包含公式，值將根據該公式進行更新。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)