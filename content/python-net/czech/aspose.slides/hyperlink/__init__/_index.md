---
title: Hyperlink constructor
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Vytvoří instanci hypertextového odkazu.

```python
def __init__(self, url):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| url | **str** | URL hypertextového odkazu. |

## __init__(self, slide) {#islide}
Vytvoří instanci hypertextového odkazu, která odkazuje na konkrétní snímek.
Poznámka: vytvořený hypertextový odkaz by měl být přiřazen k nějakému objektu ze stejné prezentace, jinak bude odkaz uložen jako NoAction.

```python
def __init__(self, slide):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Cílový snímek. |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Vytvoří instanci hypertextového odkazu pomocí jiného hypertextového odkazu jako zdroje, přepisuje sekundární vlastnosti.

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink) | Zdrojový hypertextový odkaz |
| target_frame | **str** | Cílový rámec |
| tooltip | **str** | Text popisku |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### Viz také
* třída [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)