---
title: Hyperlink constructor
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Maakt een instantie van een hyperlink aan.

```python
def __init__(self, url):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| url | **str** | Hyperlink URL. |

## __init__(self, slide) {#islide}
Maakt een instantie van een hyperlink die naar een specifieke dia verwijst.
            Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.

```python
def __init__(self, slide):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Target slide. |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Maakt een instantie van een hyperlink met een andere hyperlink als bron, waarbij secundaire eigenschappen worden overschreven.

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink) | Source hyperlink |
| target_frame | **str** | Target frame |
| tooltip | **str** | Tooltip text |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### Zie ook
* klasse [`Hyperlink`](/slides/python-net/nl/aspose.slides/hyperlink)
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)