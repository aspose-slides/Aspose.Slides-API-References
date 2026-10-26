---
title: SvgImage constructor
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/svgimage/__init__/
weight: 10
---
## __init__(self, data) {#bytes}
Erstellt ein neues SvgImage-Objekt.


```python
def __init__(self, data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | **bytes** | Svg-Daten. |


## __init__(self, svg_content) {#str}
Erstellt ein neues SvgImage-Objekt.


```python
def __init__(self, svg_content):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| svg_content | **str** | Svg-Inhalt. |


## __init__(self, stream) {#iorawiobase}
Erstellt ein neues SvgImage-Objekt.


```python
def __init__(self, stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg-Stream. |


## __init__(self, data, external_res_resolver, base_uri) {#bytes-asposeslidesimportingiexternalresourceresolver-str}
Erstellt ein neues SvgImage-Objekt.


```python
def __init__(self, data, external_res_resolver, base_uri):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | **bytes** | Svg-Daten. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| base_uri | **str** | Basis-URI des angegebenen Svg. Wird verwendet, um relative Links aufzulösen. |


## __init__(self, svg_content, external_res_resolver, base_uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Erstellt ein neues SvgImage-Objekt.


```python
def __init__(self, svg_content, external_res_resolver, base_uri):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| svg_content | **str** | Svg-Inhalt. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| base_uri | **str** | Basis-URI des angegebenen Svg. Wird verwendet, um relative Links aufzulösen. |


## __init__(self, stream, external_res_resolver, base_uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Erstellt ein neues SvgImage-Objekt.


```python
def __init__(self, stream, external_res_resolver, base_uri):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg-Stream. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| base_uri | **str** | Basis-URI des angegebenen Svg. Wird verwendet, um relative Links aufzulösen. |



### Siehe auch
* Klasse [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver)
* Klasse [`SvgImage`](/slides/python-net/de/aspose.slides/svgimage)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)