---
title: IChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection 類別

表示 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory) 的集合

The IChartCategoryCollection type exposes the following members:

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`use_cells`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/use_cells/) | 如果為 true，則使用工作表來存儲類別（此情況支援多層類別）。<br/>如果為 false，則工作表不會用於存儲值（此情況不支援<br/>多層類別）。<br/>可讀寫 **bool**。 |
| [`grouping_level_count`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | 傳回使用的類別分組層級數量。<br/>對於多層類別，此值大於一。<br/>唯讀 **int**。 |

取得指定索引處的元素。

## 索引子

| 名稱 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | 如果集合中已存在類別，則傳回它。否則從<br/>[`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) 建立新的圖表類別並將其加入集合。 |
| [`add(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/add/#any) | 從值建立新的 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory) 並將其加入集合。 |
| [`index_of(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | 搜尋指定的 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory)，並傳回整個集合中首次出現的零基索引。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | 移除指定的值。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | 移除給定索引處的元素。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection/clear/#) | 移除集合中的所有元素。 |

### 另請參閱
* 類別 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)