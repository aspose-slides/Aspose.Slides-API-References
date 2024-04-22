---
title: SvgImage constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/svgimage/__init__/
weight: 10
---


## __init__ {#bytes}
Creates new SvgImage object.


```python
def __init__(self, data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| data | **bytes** | Svg data. |


## __init__ {#str}
Creates new SvgImage object.


```python
def __init__(self, svg_content):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_content | **str** | Svg content. |


## __init__ {#iorawiobase}
Creates new SvgImage object.


```python
def __init__(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg stream. |


## __init__ {#bytes-asposeslidesimportingiexternalresourceresolver-str}
Creates new SvgImage object.


```python
def __init__(self, data, external_res_resolver, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| data | **bytes** | Svg data. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| base_uri | **str** | Base URI of the specified Svg. Used to resolve relative links. |


## __init__ {#str-asposeslidesimportingiexternalresourceresolver-str}
Creates new SvgImage object.


```python
def __init__(self, svg_content, external_res_resolver, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_content | **str** | Svg content. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| base_uri | **str** | Base URI of the specified Svg. Used to resolve relative links. |


## __init__ {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Creates new SvgImage object.


```python
def __init__(self, stream, external_res_resolver, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg stream. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| base_uri | **str** | Base URI of the specified Svg. Used to resolve relative links. |



### See Also
* class [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver)
* class [`SvgImage`](/slides/python-net/aspose.slides/svgimage)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

