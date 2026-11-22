---
title: IDataLabel class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabel/
---
## IDataLabel 類別

表示系列標籤。

IDataLabel 類型公開以下成員：

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/is_visible/) | False 表示資料標籤不可見（因此所有 Show*-flags（如 ShowValue，...）皆為 false）。<br/>            唯讀 **bool**。 |
| [`data_label_format`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/data_label_format/) | 返回資料標籤的格式。<br/>            唯讀 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)。 |
| [`value_from_cell`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/value_from_cell/) | 取得或設定工作簿資料儲存格。當 IDataLabelFormat.ShowLabelValueFromCell 屬性 為 true 時套用。 |
| [`label_shape_type`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/label_shape_type/) | 取得或設定資料標籤的圖形類型。<br/>            如果未定義圖形，則返回 [`ShapeType.NOT_DEFINED`](/slides/python-net/zh-hant/aspose.slides/shapetype/NOT_DEFINED)。 |
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

| 方法 | 描述 |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/hide/#) | 透過將所有 Show*-flags（如 ShowValue，...）設定為 false 來隱藏資料標籤。<br/>            之後 IsVisible 將為 false。 |
| [`get_actual_label_text(self)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/get_actual_label_text/#) | 根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值返回實際的標籤文字。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)