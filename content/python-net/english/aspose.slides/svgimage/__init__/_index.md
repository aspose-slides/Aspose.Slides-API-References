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
| data | bytes | Svg data. |



## __init__ {#string}
Creates new SvgImage object.


```python
def __init__(self, svg_content):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_content | string | Svg content. |



## __init__ {#systemiostream}
Creates new SvgImage object.


```python
def __init__(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Svg stream. |



## __init__ {#bytes-asposeslidesimportingiexternalresourceresolver-string}
Creates new SvgImage object.


```python
def __init__(self, data, external_res_resolver, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| data | bytes | Svg data. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| base_uri | string | Base URI of the specified Svg. Used to resolve relative links. |



## __init__ {#string-asposeslidesimportingiexternalresourceresolver-string}
Creates new SvgImage object.


```python
def __init__(self, svg_content, external_res_resolver, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_content | string | Svg content. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| base_uri | string | Base URI of the specified Svg. Used to resolve relative links. |



## __init__ {#systemiostream-asposeslidesimportingiexternalresourceresolver-string}
Creates new SvgImage object.


```python
def __init__(self, stream, external_res_resolver, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Svg stream. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| base_uri | string | Base URI of the specified Svg. Used to resolve relative links. |



