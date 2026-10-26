---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
从 HTML 文本创建幻灯片并将其添加到集合的末尾。

### 返回值

已添加的幻灯片



```python
def add_from_html(self, html_text):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| html_text | **str** | 要添加的 HTML。 |


## add_from_html(self, html_stream) {#iorawiobase}
从 HTML 文本创建幻灯片并将其添加到集合的末尾。

### 返回值

已添加的幻灯片



```python
def add_from_html(self, html_stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | 将用作 HTML 文件来源的流对象。 |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
从 HTML 文本创建幻灯片并将其添加到集合的末尾。

### 返回值

已添加的幻灯片。



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| html_text | **str** | 要添加的 HTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则所有外部对象将被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
从 HTML 文本创建幻灯片并将其添加到集合的末尾。

### 返回值

已添加的幻灯片。



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | 将用作 HTML 文件来源的流对象。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则所有外部对象将被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |



### 另见
* 类 [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver)
* 类 [`SlideCollection`](/slides/python-net/zh/aspose.slides/slidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)