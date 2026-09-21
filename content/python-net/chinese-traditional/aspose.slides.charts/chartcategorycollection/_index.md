---
title: ChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection 類別

表示 [`ChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory) 的集合

ChartCategoryCollection 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`use_cells`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/use_cells/) | 如果為 true，則工作表用於儲存類別（此情況支援多層類別）。<br/>            如果為 false，則工作表不會用於儲存值（此情況不支援<br/>            多層類別）。<br/>            可讀寫 **bool**。 |
| [`grouping_level_count`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | 回傳使用的類別分組層級數量。<br/>            多層類別時會大於一。<br/>            唯讀 **int**。 |

取得指定索引處的元素。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | 如果類別已存在於集合中，則返回它。否則從<br/>            [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) 建立新的圖表類別並將其加入集合。 |
| [`add(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/add/#any) | 從值建立新的 [`ChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory) 並將其加入集合。 |
| [`index_of(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | 搜尋指定的 [`ChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory)，並回傳在整個集合中第一次出現的零基索引。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | 移除指定的值。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/remove_at/#int) | 移除給定索引處的元素。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection/clear/#) | 從集合中移除所有元素。 |

### 另請參閱
* 類別 [`ChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)