---
title: Hyperlink constructor
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Crea una instancia de un hipervínculo.


```python
def __init__(self, url):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| url | **str** | URL del hipervínculo. |


## __init__(self, slide) {#islide}
Crea una instancia de un hipervínculo que apunta a una diapositiva específica.
Nota: el hipervínculo creado debe asignarse a algún objeto de la misma presentación, de lo contrario el enlace se guardará como NoAction.


```python
def __init__(self, slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva de destino. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Crea una instancia de un hipervínculo usando otro hipervínculo como origen, sobrescribiendo propiedades secundarias.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink) | Hipervínculo de origen |
| target_frame | **str** | Marco de destino |
| tooltip | **str** | Texto de información sobre herramienta |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Ver también
* clase [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)