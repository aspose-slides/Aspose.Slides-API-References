---
title: DoubleChartValue class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/doublechartvalue/
---
## DoubleChartValue 類別

代表可在 pptx 簡報文件中以兩種方式儲存的雙精度值：
            1) 位於與圖表相關的工作簿儲存格/儲存格；
            2) 作為文字值。

**繼承:**[`DoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/doublechartvalue) → [`BaseChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/basechartvalue)

DoubleChartValue 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`data_source_type`](/slides/python-net/zh-hant/aspose.slides.charts/doublechartvalue/data_source_type/) | 指定在衍生類別中實際使用 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble <br/>            屬性。換句話說，它指定 Data 屬性的值類型。<br/>            讀寫 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype)。 |
| [`data`](/slides/python-net/zh-hant/aspose.slides.charts/doublechartvalue/data/) | 取得或設定 Data 物件。<br/>            讀寫 **any**。 |
| [`as_cell`](/slides/python-net/zh-hant/aspose.slides.charts/doublechartvalue/as_cell/) | 取得或設定圖表資料儲存格。<br/>            讀寫 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal_double`](/slides/python-net/zh-hant/aspose.slides.charts/doublechartvalue/as_literal_double/) | 取得或設定以文字雙精度表示的值。<br/>            讀寫 **float**。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`to_double(self)`](/slides/python-net/zh-hant/aspose.slides.charts/doublechartvalue/to_double/#) | 轉換為 **float**。 |

### 另見
* 類別 [`BaseChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/basechartvalue)
* 類別 [`DoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/doublechartvalue)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)