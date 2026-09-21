---
title: Hyperlink constructor
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
建立超連結的實例。

```python
def __init__(self, url):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| url | **str** | 超連結 URL。 |

## __init__(self, slide) {#islide}
建立指向特定投影片的超連結實例。  
注意：建立的超連結應指派給同一簡報中的某個物件，否則連結將儲存為 NoAction。

```python
def __init__(self, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 目標投影片。 |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
使用另一個超連結作為來源，覆寫次要屬性來建立超連結實例。

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink) | 來源超連結 |
| target_frame | **str** | 目標框架 |
| tooltip | **str** | 工具提示文字 |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### 另請參閱
* 類別 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)