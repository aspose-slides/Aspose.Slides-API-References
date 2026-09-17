---
title: SvgImage constructor
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/svgimage/__init__/
weight: 10
---
## __init__(self, data) {#bytes}
创建新的 SvgImage 对象。


```python
def __init__(self, data):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data | **bytes** | Svg 数据。 |


## __init__(self, svg_content) {#str}
创建新的 SvgImage 对象。


```python
def __init__(self, svg_content):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| svg_content | **str** | Svg 内容。 |


## __init__(self, stream) {#iorawiobase}
创建新的 SvgImage 对象。


```python
def __init__(self, stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg 流。 |


## __init__(self, data, external_res_resolver, base_uri) {#bytes-asposeslidesimportingiexternalresourceresolver-str}
创建新的 SvgImage 对象。


```python
def __init__(self, data, external_res_resolver, base_uri):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data | **bytes** | Svg 数据。 |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则会忽略所有外部对象。 |
| base_uri | **str** | 指定 Svg 的基 URI。用于解析相对链接。 |


## __init__(self, svg_content, external_res_resolver, base_uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
创建新的 SvgImage 对象。


```python
def __init__(self, svg_content, external_res_resolver, base_uri):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| svg_content | **str** | Svg 内容。 |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则会忽略所有外部对象。 |
| base_uri | **str** | 指定 Svg 的基 URI。用于解析相对链接。 |


## __init__(self, stream, external_res_resolver, base_uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
创建新的 SvgImage 对象。


```python
def __init__(self, stream, external_res_resolver, base_uri):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg 流。 |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 None，则会忽略所有外部对象。 |
| base_uri | **str** | 指定 Svg 的基 URI。用于解析相对链接。 |



### 参见
* 类 [`IExternalResourceResolver`](/slides/python-net/zh/aspose.slides.importing/iexternalresourceresolver)
* 类 [`SvgImage`](/slides/python-net/zh/aspose.slides/svgimage)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)