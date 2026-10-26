---
title: Hyperlink constructor
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Skapar en instans av en hyperlänk.


```python
def __init__(self, url):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| url | **str** | Hyperlänkens URL. |


## __init__(self, slide) {#islide}
Skapar en instans av en hyperlänk som pekar på en specifik bild.
Obs: den skapade hyperlänken bör tilldelas ett objekt från samma presentation, annars sparas länken som NoAction.


```python
def __init__(self, slide):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Målbild. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Skapar en instans av en hyperlänk med en annan hyperlänk som källa, och åsidosätter sekundära egenskaper.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink) | Källhyperlänk |
| target_frame | **str** | Målram |
| tooltip | **str** | Verktygstippstext |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Se också
* klass [`Hyperlink`](/slides/python-net/sv/aspose.slides/hyperlink)
* klass [`ISlide`](/slides/python-net/sv/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)