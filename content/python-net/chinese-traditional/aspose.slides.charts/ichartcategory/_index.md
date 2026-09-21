---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartcategory/
---
## IChartCategory 類別

表示圖表類別。

The IChartCategory type exposes the following members:

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`use_cell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/use_cell/) | 如果為 true，則 AsCell 屬性為實際值。換句話說，worksheet 用於 <br/>            儲存類別（此情況支援多層類別）。<br/>            如果為 false，則 AsLiteral 屬性為實際值。換句話說，worksheet **不** 用於 <br/>            儲存類別（此情況不支援多層類別）。<br/>            唯讀 **bool**。 |
| [`as_cell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/as_cell/) | 傳回或設定 IChartDataCell 物件。<br/>            如果類別為多層，則使用 level "0" 的 IChartDataCell 物件。<br/>            可讀寫 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/as_literal/) | 如果 UseCell 為 false，則傳回或設定 AsLiteral。<br/>            可讀寫 **any**。 |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/value/) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。<br/>            如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。<br/>            可讀寫 **any**。 |
| [`grouping_levels`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/grouping_levels/) | 受管理的容器，存放圖表類別分組層級的值。<br/>            多層類別包含多個分組層級。<br/>            分組層級索引從零開始。<br/>            唯讀 [`IChartCategoryLevelsManager`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorylevelsmanager)。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory/remove/#) | 從圖表中移除類別。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)