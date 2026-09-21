---
title: StringChartValue class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/stringchartvalue/
---
## StringChartValue 類別

表示可以以兩種方式儲存在 pptx 簡報文件中的字串值：
1) 在與圖表相關的工作簿之儲存格/儲存格集合中；
2) 作為文字字面值。

**繼承：**[`StringChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/basechartvalue)

StringChartValue 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`data_source_type`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue/data_source_type/) | 指定在子類別中哪個 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble <br/>            屬性實際存在。換句話說，它指定 Data 屬性值的類型 <br/>            。<br/>            讀/寫 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype)。 |
| [`data`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue/data/) | 返回或設定 Data 物件。<br/>            讀/寫 **任意**。 |
| [`as_cells`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue/as_cells/) | 不允許指派 Null 值。<br/>            返回的值總是非 None。<br/>            讀/寫 [`IChartCellCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcellcollection)。 |
| [`as_literal_string`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue/as_literal_string/) | 返回或設定值為文字字面值。<br/>            讀/寫 **str**。 |

## 方法

| Method | Description |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | 從指定的儲存格設定值。 |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | 如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法返回工作簿中代表字串資料的儲存格地址<br/>            。否則返回<br/>            空字串。 |

### 另見
* 類別 [`BaseChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/basechartvalue)
* 類別 [`StringChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/stringchartvalue)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)