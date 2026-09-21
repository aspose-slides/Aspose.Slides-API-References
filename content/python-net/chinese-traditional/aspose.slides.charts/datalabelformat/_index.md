---
title: DataLabelFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat 類別

表示 DataLabel 的格式化選項。

**繼承:**[`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

DataLabelFormat 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/) | 讀寫 **bool**. |
| [`number_format`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/number_format/) | 表示 DataLabels 物件的格式字串。<br/>            讀寫 **str**. |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/format/) | 表示資料標籤的格式。<br/>            唯讀 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/position/) | 表示資料標籤的位置。<br/>            讀寫 [`LegendDataLabelPosition`](/slides/python-net/zh-hant/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_legend_key/) | 表示特定圖表的資料標籤圖例鍵顯示行為。 <br/>            如果資料標籤圖例鍵可見則為 True。<br/>            讀寫 **bool**. |
| [`show_value`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_value/) | 表示特定圖表的資料標籤百分比值顯示行為。 <br/>            True 顯示百分比值。False 隱藏。<br/>            讀寫 **bool**. |
| [`show_category_name`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_category_name/) | 表示特定圖表的資料標籤類別名稱顯示行為。<br/>            True 顯示圖表上資料標籤的類別名稱。False 隱藏。<br/>            讀寫 **bool**. |
| [`show_series_name`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_series_name/) | 傳回或設定布林值以指示圖表上資料標籤的系列名稱顯示行為。 <br/>            True 顯示系列名稱。False 隱藏。<br/>            讀寫 **bool**. |
| [`show_percentage`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_percentage/) | 表示特定圖表的資料標籤百分比值顯示行為。 <br/>            True 顯示百分比值。False 隱藏。<br/>            讀寫 **bool**. |
| [`show_bubble_size`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_bubble_size/) | 表示特定圖表的資料標籤泡泡大小值顯示行為。 <br/>            True 顯示泡泡大小值。False 隱藏。<br/>            讀寫 **bool**. |
| [`show_leader_lines`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_leader_lines/) | 表示特定圖表的資料標籤指示線顯示行為。 <br/>            True 顯示指示線。False 隱藏。<br/>            讀寫 **bool**. |
| [`show_label_value_from_cell`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_label_value_from_cell/) | 表示特定圖表的資料標籤儲存格值顯示行為。 <br/>            True 顯示儲存格值。False 隱藏。<br/>            讀寫 **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/show_label_as_data_callout/) | 決定特定圖表的資料標籤是顯示為資料註解還是資料標籤。<br/>            <br/>            如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定新資料標籤在 DataLabelCollection 集合中的 ShowLabelAsDataCallout 屬性的預設值。<br/>            設定此屬性的值同時會將此值設定給 DataLabelCollection 集合中所有資料標籤的 ShowLabelAsDataCallout 屬性<br/>            (例如 "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 會導致 <br/>            所有 DataLabels[i].ShowLabelAsDataCallout 等於 val)。 |
| [`separator`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/separator/) | 設定或傳回代表圖表上資料標籤所使用分隔符的 Variant。<br/>            讀寫 **str**. |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/text_format/) | 傳回圖表文字格式。<br/>            唯讀 [`IChartTextFormat`](/slides/python-net/zh-hant/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/chart/) | 傳回圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat/presentation/) |  |

### 另見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)