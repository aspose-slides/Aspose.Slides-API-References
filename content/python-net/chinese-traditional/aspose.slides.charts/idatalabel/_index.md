---
title: IDataLabel class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabel/
---
## IDataLabel 類別

表示系列標籤。

IDataLabel 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/is_visible/) | False 表示資料標籤不可見（因此所有 Show*-flags（ShowValue，...）皆為 false）。<br/>            唯讀 **bool**. |
| [`data_label_format`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/data_label_format/) | 傳回資料標籤的格式。<br/>            唯讀 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/value_from_cell/) | 取得或設定工作簿資料儲存格。如果 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true，則套用此設定。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/actual_height/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/hide/#) | 透過將所有 Show*-flags（ShowValue，...）設定為 false，將資料標籤隱藏。<br/>            IsVisible 將在此之後為 false. |
| [`get_actual_label_text(self)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/get_actual_label_text/#) | 根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 的值傳回實際的標籤文字。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### 參見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)