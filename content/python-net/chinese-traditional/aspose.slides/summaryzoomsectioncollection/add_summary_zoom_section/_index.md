---
title: add_summary_zoom_section method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
建立新的 Summary Zoom Section 物件並將其新增至集合

### 返回值

已新增 [`ISummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isummaryzoomframe) 元素



```python
def add_summary_zoom_section(self, section):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 用於新 Summary Zoom Section 元素的 Section [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) |

### 備註

如果集合中已存在此 section 的元素，則回傳現有的元素。

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 參考的 section 不屬於目前的簡報或不包含任何投影片。 |



### 參見
* 類別 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)
* 類別 [`ISummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isummaryzoomframe)
* 類別 [`ISummaryZoomSection`](/slides/python-net/zh-hant/aspose.slides/isummaryzoomsection)
* 類別 [`SummaryZoomSectionCollection`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsectioncollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)