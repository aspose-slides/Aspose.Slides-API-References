---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
從指定的 HTML 字串將文字新增至集合。

```python
def add_from_html(self, text):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| text | **str** | HTML 文字。 |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
從指定的 HTML 字串將文字新增至集合。

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| text | **str** | HTML 文字。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 解析 URI 並取得參考物件的回呼解析器物件。 |
| uri | **str** | 用於新增 HTML 文件的 URI。用於解析相對連結。 |

### 備註

指定解析器可能會導致安全性漏洞。使用時請謹慎。

### 另見
* 類別 [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver)
* 類別 [`ParagraphCollection`](/slides/python-net/zh-hant/aspose.slides/paragraphcollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)