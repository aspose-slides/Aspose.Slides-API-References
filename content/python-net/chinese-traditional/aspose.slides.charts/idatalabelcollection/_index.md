---
title: IDataLabelCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection 類別

表示系列標籤。

IDataLabelCollection 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | 傳回集合中所有資料標籤的預設格式。<br/>            唯讀 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)。 |
| [`leader_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | 表示資料標籤領線格式。<br/>            唯讀 [`IChartLinesFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ichartlinesformat)。 |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/is_visible/) | False 表示資料標籤預設不可見（因此 DefaultDataLabelFormat 屬性的所有 Show* 標誌 (ShowValue, ...) 為 false）。<br/>            唯讀 **bool**。 |
| [`count_of_visible_data_labels`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | 取得集合中可見資料標籤的數量。<br/>            唯讀 **int**。 |
| [`count`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/count/) | 取得集合中全部資料標籤的數量。<br/>            唯讀 **int**。 |
| [`parent_series`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/parent_series/) | 傳回父圖表系列。<br/>            唯讀 [`IChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries)。 |
| [`default_label_shape_type`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | 取得或設定資料標籤的預設圖形類型。<br/>            若未定義圖形，則傳回 [`ShapeType.NOT_DEFINED`](/slides/python-net/zh-hant/aspose.slides/shapetype/NOT_DEFINED)。 |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/presentation/) |  |

取得具有指定索引的資料點之資料標籤。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/hide/#) | 透過將 DefaultDataLabelFormat 屬性的所有 Show* 標誌 (ShowValue, ...) 設為 false，使資料標籤預設為隱藏。<br/>            之後 IsVisible 將為 false。 |
| [`index_of(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | 傳回集合中指定 DataLabel 的索引。 |

### 參見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)