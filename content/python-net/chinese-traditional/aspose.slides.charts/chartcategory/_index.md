---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartcategory/
---
## ChartCategory 類別

表示圖表類別。

ChartCategory 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`use_cell`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/use_cell/) | 如果為 true，則 AsCell 屬性為實際值。換句話說，工作表用於<br/>            儲存類別（此情況支援多層類別）。<br/>            如果為 false，則 AsLiteral 屬性為實際值。換句話說，工作表**不**用於<br/>            儲存類別（此情況不支援多層類別）。<br/>            唯讀 **bool**。 |
| [`as_cell`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/as_cell/) | 取得或設定 IChartDataCell 物件。<br/>            如果類別是多層的，則使用等級「0」的 IChartDataCell 物件。<br/>            可讀寫 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/as_literal/) | 取得或設定 AsLiteral 物件。<br/>            可讀寫 **any**。 |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/value/) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。<br/>            如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。<br/>            可讀寫 **any**。 |
| [`grouping_levels`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/grouping_levels/) | 圖表類別分組層級的值的受管理容器。<br/>            多層類別包含多於一個分組層級。<br/>            分組層級索引以零為起點。<br/>            唯讀 [`IChartCategoryLevelsManager`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorylevelsmanager)。 |
| [`cached_value`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/cached_value/) | 取得圖表類別的快取值。<br/>            唯讀 [`ICachedChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/icachedchartvalue)。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/remove/#) | 從圖表中移除類別。 |


### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)