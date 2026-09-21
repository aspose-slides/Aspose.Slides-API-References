---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartcategory/
---
## ChartCategory 類別

Represents chart categories.

The ChartCategory type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/use_cell/) | 如果為 true，則 AsCell 屬性為實際值。換句話說，工作表用於 <br/> 儲存類別（此情況支援多層級類別）。<br/> 如果為 false，則 AsLiteral 屬性為實際值。換句話說，工作表 **不** 用於 <br/> 儲存類別（此情況不支援多層級類別）。<br/> 只讀 **bool**. |
| [`as_cell`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/as_cell/) | 傳回或設定 IChartDataCell 物件。<br/> 如果類別為多層級，則使用 IChartDataCell 物件於等級 "0"。<br/> 讀寫 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/as_literal/) | 傳回或設定 AsLiteral 物件。<br/> 讀寫 **any**. |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/value/) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。<br/> 如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。<br/> 讀寫 **any**. |
| [`grouping_levels`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/grouping_levels/) | 受管理的容器，儲存圖表類別分組層級的值。<br/> 多層級類別包含多於一個分組層級。<br/> 分組層級索引從零開始。<br/> 只讀 [`IChartCategoryLevelsManager`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorylevelsmanager). |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory/remove/#) | 從圖表中移除類別。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)