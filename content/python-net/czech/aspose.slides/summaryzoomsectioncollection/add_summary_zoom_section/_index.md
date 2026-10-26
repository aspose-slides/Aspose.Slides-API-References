---
title: add_summary_zoom_section method
second_title: Aspose.Slides pro Python pomocí .NET API
description: 
type: docs
url: /cs/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
Vytvoří nový objekt Summary Zoom Section a přidá jej do kolekce

### Returns

Přidaný [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe) element



```python
def add_summary_zoom_section(self, section):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | Sekce pro nový [`ISection`](/slides/python-net/cs/aspose.slides/isection) element Summary Zoom Section |

### Remarks

Pokud pro tuto sekci již v kolekci existuje element, vrátí se existující element.

### Exceptions

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Odkazovaná sekce nepatří do aktuální prezentace nebo neobsahuje žádné snímky. |



### See Also
* třída [`ISection`](/slides/python-net/cs/aspose.slides/isection)
* třída [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe)
* třída [`ISummaryZoomSection`](/slides/python-net/cs/aspose.slides/isummaryzoomsection)
* třída [`SummaryZoomSectionCollection`](/slides/python-net/cs/aspose.slides/summaryzoomsectioncollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)