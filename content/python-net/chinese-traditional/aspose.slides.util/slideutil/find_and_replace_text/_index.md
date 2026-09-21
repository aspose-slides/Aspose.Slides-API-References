---
title: find_and_replace_text method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.util/slideutil/find_and_replace_text/
weight: 20
---
## find_and_replace_text(presentation, with_masters, find, replace, format) {#ipresentation-bool-str-str-portionformat}
找出並取代簡報中符合指定格式的文字


```python
@staticmethod
def find_and_replace_text(presentation, with_masters, find, replace, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) | 已掃描的簡報。 |
| with_masters | **bool** | 決定是否應掃描母片投影片。 |
| find | **str** | 要搜尋的字串值。 |
| replace | **str** | 要取代的字串值。 |
| format | [`PortionFormat`](/slides/python-net/zh-hant/aspose.slides/portionformat) | 用於取代文字部分的格式。若為 None，則會使用搜尋字串第一個 <br/><br/>            字元的格式。 |



### 另見
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`PortionFormat`](/slides/python-net/zh-hant/aspose.slides/portionformat)
* 類別 [`SlideUtil`](/slides/python-net/zh-hant/aspose.slides.util/slideutil)
* 模組 [`aspose.slides.util`](/slides/python-net/zh-hant/aspose.slides.util)
* 函式庫 [`Aspose.Slides`](/slides/python-net)