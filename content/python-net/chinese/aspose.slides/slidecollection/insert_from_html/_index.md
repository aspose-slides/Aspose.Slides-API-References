---
title: insert_from_html method
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片



```python
def insert_from_html(self, index, html_text):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_text | **str** | 要添加的 Html。 |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片



```python
def insert_from_html(self, index, html_stream):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_stream | **io.RawIOBase** | 用于作为 HTML 文件来源的 Stream 对象。 |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_text | **str** | 要添加的 Html。 |
| use_slide_with_index_as_start | **bool** | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides。 |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_stream | **io.RawIOBase** | 用于作为 HTML 文件来源的 Stream 对象。 |
| use_slide_with_index_as_start | **bool** | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides。 |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片。



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_text | **str** | 要添加的 Html。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则所有外部对象将被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片。



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_stream | **io.RawIOBase** | 用于作为 HTML 文件来源的 Stream 对象。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则所有外部对象将被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片。



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_text | **str** | 要添加的 Html。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则所有外部对象将被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |
| use_slide_with_index_as_start | **bool** | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides。 |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
从 HTML 文本创建幻灯片并将它们插入到集合中的指定位置。

### 返回

已添加的幻灯片。



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 说明 |
| :- | :- | :- |
| index | **int** | 要插入的位置。 |
| html_stream | **io.RawIOBase** | 用于作为 HTML 文件来源的 Stream 对象。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则所有外部对象将被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |
| use_slide_with_index_as_start | **bool** | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides。 |



### 另见
* 类 [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver)
* 类 [`SlideCollection`](/slides/python-net/zh/aspose.slides/slidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)