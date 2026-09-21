---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
將指定的 HTML 文字加入至集合中。

```python
def add_from_html(self, text):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| text | **str** | HTML 文字。 |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
將指定的 HTML 文字加入至集合中。

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| text | **str** | HTML 文字。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 解析 URI 並擷取參照物件的 resolver 回呼物件。 |
| uri | **str** | 用於加入 HTML 文件的 URI。用於解析相對連結。 |

### 備註

指定 resolver 可能會導致漏洞。請謹慎使用。

### 另請參閱
* 類別 [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver)
* 類別 [`IParagraphCollection`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)