---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
将指定的 html 字符串中的文本添加到集合中。

```python
def add_from_html(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | **str** | HTML 文本。 |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
将指定的 html 字符串中的文本添加到集合中。

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | **str** | HTML 文本。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | Resolver 回调对象，用于解析 URI 并获取引用对象。 |
| uri | **str** | 用于添加 HTML 文档的 URI。用于解析相对链接。 |

### 备注

指定 resolver 可能会引入漏洞。请谨慎使用。

### 另请参见
* 类 [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver)
* 类 [`IParagraphCollection`](/slides/python-net/zh/aspose.slides/iparagraphcollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)