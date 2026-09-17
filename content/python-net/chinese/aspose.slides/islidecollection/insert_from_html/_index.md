---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片



```python
def insert_from_html(self, index, html_text):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要添加的 HTML。 |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片



```python
def insert_from_html(self, index, html_stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 将用作 HTML 文件来源的 Stream 对象。 |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要添加的 HTML。 |
| use_slide_with_index_as_start | **bool** | 此标志决定如何开始插入：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>            如果 **true** , 则数据插入将从具有指定索引的幻灯片的空白处开始。<br/><br/>            如果 **false** , 则数据将添加到创建的幻灯片中。 |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 将用作 HTML 文件来源的 Stream 对象。 |
| use_slide_with_index_as_start | **bool** | 此标志决定如何开始插入：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>            如果 **true** , 则数据插入将从具有指定索引的幻灯片的空白处开始。<br/><br/>            如果 **false** , 则数据将添加到创建的幻灯片中。 |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片。



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要添加的 HTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，将忽略所有外部对象。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片。



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 将用作 HTML 文件来源的 Stream 对象。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，将忽略所有外部对象。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片。



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要添加的 HTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，将忽略所有外部对象。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |
| use_slide_with_index_as_start | **bool** | 此标志决定如何开始插入：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>            如果 **true** , 则数据插入将从具有指定索引的幻灯片的空白处开始。<br/><br/>            如果 **false** , 则数据将添加到创建的幻灯片中。 |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。

### 返回值

已添加的幻灯片。



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 将用作 HTML 文件来源的 Stream 对象。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，将忽略所有外部对象。 |
| uri | **str** | 指定 HTML 的 URI。用于解析相对链接。 |
| use_slide_with_index_as_start | **bool** | 此标志决定如何开始插入：从新幻灯片或从具有指定索引的幻灯片。<br/><br/>            如果 **true** , 则数据插入将从具有指定索引的幻灯片的空白处开始。<br/><br/>            如果 **false** , 则数据将添加到创建的幻灯片中。 |



### 另见
* 类 [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver)
* 类 [`ISlideCollection`](/slides/python-net/zh/aspose.slides/islidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)