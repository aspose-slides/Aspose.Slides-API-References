---
title: IStringChartValue class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue 類別

表示可以以兩種方式儲存在 pptx 簡報文件中的字串值：
1) 在與圖表相關的活頁簿的儲存格中；
2) 作為文字值。

IStringChartValue 類型會公開以下成員：

## 屬性

| Property | 說明 |
| :- | :- |
| [`as_literal_string`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue/as_literal_string/) | 如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則返回或設定文字字面值。<br/>            可讀寫 **str**. |
| [`as_cells`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue/data/) |  |

## 方法

| Method | 說明 |
| :- | :- |
| [`to_string(self)`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue/to_string/#) | 返回字串表示。 |
| [`set_from_one_cell(self, cell)`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | 從指定的儲存格設定值。 |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | 如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法返回<br/>            活頁簿中代表字串資料的儲存格位址。否則返回<br/>            空字串。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)