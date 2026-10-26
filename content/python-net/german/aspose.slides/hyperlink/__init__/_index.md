---
title: Hyperlink constructor
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Erstellt eine Instanz eines Hyperlinks.


```python
def __init__(self, url):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| url | **str** | Hyperlink-URL. |


## __init__(self, slide) {#islide}
Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist.  
Hinweis: Der erstellte Hyperlink sollte einem Objekt derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert.


```python
def __init__(self, slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Zielfolie. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Erstellt eine Instanz eines Hyperlinks unter Verwendung eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink) | Quellhyperlink |
| target_frame | **str** | Zielrahmen |
| tooltip | **str** | Tooltip-Text |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Siehe auch
* Klasse [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink)
* Klasse [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)