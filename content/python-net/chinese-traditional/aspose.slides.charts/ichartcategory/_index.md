---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartcategory/
---
## IChartCategory 類別

表示圖表類別。

IChartCategory 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/use_cell/) | 如果為 true，則 AsCell 屬性為實際。<br/>            換句話說，工作表用於儲存類別（此情況支援多層類別）。<br/>            如果為 false，則 AsLiteral 屬性為實際。<br/>            換句話說，工作表不會被用來儲存類別（且此情況不支援多層類別）。<br/>            唯讀 **bool**. |
| [`as_cell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/as_cell/) | 傳回或設定 IChartDataCell 物件。<br/>            如果類別是多層的，則在等級 "0" 使用 IChartDataCell 物件。<br/>            讀寫 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/as_literal/) | 傳回或設定 AsLiteral（若 UseCell 為 false）。<br/>            讀寫 **any**. |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/value/) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。<br/>            如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。<br/>            讀寫 **any**. |
| [`cached_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/cached_value/) | 取得圖表類別的緩存值。<br/>            唯讀 [`ICachedChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/grouping_levels/) | 圖表類別分組層級值的受管容器。<br/>            多層類別包含多於一個分組層級。<br/>            分組層級的索引從零開始。<br/>            唯讀 [`IChartCategoryLevelsManager`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorylevelsmanager). |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/remove/#) | 從圖表中移除類別。 |

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)