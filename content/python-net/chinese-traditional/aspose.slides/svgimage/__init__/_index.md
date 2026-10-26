---
title: SvgImage constructor
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/svgimage/__init__/
weight: 10
---
## __init__(self, data) {#bytes}
建立新的 SvgImage 物件。


```python
def __init__(self, data):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| data | **bytes** | Svg 資料。 |


## __init__(self, svg_content) {#str}
建立新的 SvgImage 物件。


```python
def __init__(self, svg_content):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| svg_content | **str** | Svg 內容。 |


## __init__(self, stream) {#iorawiobase}
建立新的 SvgImage 物件。


```python
def __init__(self, stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg 串流。 |


## __init__(self, data, external_res_resolver, base_uri) {#bytes-asposeslidesimportingiexternalresourceresolver-str}
建立新的 SvgImage 物件。


```python
def __init__(self, data, external_res_resolver, base_uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| data | **bytes** | Svg 資料。 |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。如果此參數為 None，將忽略所有外部物件。 |
| base_uri | **str** | 指定 Svg 的基礎 URI。用於解析相對連結。 |


## __init__(self, svg_content, external_res_resolver, base_uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
建立新的 SvgImage 物件。


```python
def __init__(self, svg_content, external_res_resolver, base_uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| svg_content | **str** | Svg 內容。 |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。如果此參數為 None，將忽略所有外部物件。 |
| base_uri | **str** | 指定 Svg 的基礎 URI。用於解析相對連結。 |


## __init__(self, stream, external_res_resolver, base_uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
建立新的 SvgImage 物件。


```python
def __init__(self, stream, external_res_resolver, base_uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg 串流。 |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。如果此參數為 None，將忽略所有外部物件。 |
| base_uri | **str** | 指定 Svg 的基礎 URI。用於解析相對連結。 |



### 另請參閱
* 類別 [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver)
* 類別 [`SvgImage`](/slides/python-net/zh-hant/aspose.slides/svgimage)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)