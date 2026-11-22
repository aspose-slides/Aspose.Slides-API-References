---
title: DataLabelCollection class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection 類別

表示系列標籤。

DataLabelCollection 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/chart/) | 返回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/is_visible/) | False 表示資料標籤預設不可見（因此 DefaultDataLabelFormat 屬性的所有 Show*-flags（如 ShowValue 等）皆為 false）。<br/>            唯讀 **bool**。 |
| [`count_of_visible_data_labels`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | 取得集合中可見資料標籤的數量。<br/>            唯讀 **int**。 |
| [`count`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/count/) | 取得集合中所有資料標籤的數量。<br/>            唯讀 **int**。 |
| [`default_data_label_format`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/default_data_label_format/) | 取得預設資料標籤格式。<br/>            唯讀 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)。 |
| [`leader_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/leader_lines_format/) | 表示資料標籤領導線格式。<br/>            唯讀 [`IChartLinesFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ichartlinesformat)。 |
| [`parent_series`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/parent_series/) | 取得父系列。<br/>            唯讀 [`IChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries)。 |
| [`default_label_shape_type`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | 取得或設定資料標籤的預設形狀類型。<br/>            如果未定義形狀，則返回 [`ShapeType.NOT_DEFINED`](/slides/python-net/zh-hant/aspose.slides/shapetype/NOT_DEFINED)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/presentation/) |  |

取得具有指定索引的資料點之資料標籤。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/hide/#) | 將資料標籤預設設為隱藏，方法是將 DefaultDataLabelFormat 屬性的所有 Show*-flags（如 ShowValue 等）設定為 false 狀態。<br/>            此後 IsVisible 將為 false。 |
| [`index_of(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | 返回集合中指定 DataLabel 的索引。 |

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)