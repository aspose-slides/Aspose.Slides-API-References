---
title: Hyperlink constructor
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás alapján
description: 
type: docs
url: /hu/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Létrehoz egy hiperhivatkozás példányát.

```python
def __init__(self, url):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| url | **str** | Hiperhivatkozás URL-je. |

## __init__(self, slide) {#islide}
Létrehoz egy hiperhivatkozás példányát, amely egy adott diára mutat.
            Megjegyzés: a létrehozott hiperhivatkozást ugyanabból a prezentációból származó objektumhoz kell hozzárendelni, ellenkező esetben a hivatkozás NoAction-ként lesz mentve.

```python
def __init__(self, slide):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Cél dia. |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Létrehoz egy hiperhivatkozás példányát egy másik hiperhivatkozás forrásként való használatával, felülírva a másodlagos tulajdonságokat.

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink) | Forrás hiperhivatkozás |
| target_frame | **str** | Cél keret |
| tooltip | **str** | Buborékszöveg |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### Lásd még
* osztály [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)