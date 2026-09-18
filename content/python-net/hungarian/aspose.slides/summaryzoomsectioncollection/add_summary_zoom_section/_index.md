---
title: add_summary_zoom_section method
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
Új Summary Zoom Section objektumot hoz létre, és hozzáadja a gyűjteményhez

### Visszatér

Added [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe) element



```python
def add_summary_zoom_section(self, section):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | Szekció egy új Summary Zoom Section elemhez [`ISection`](/slides/python-net/hu/aspose.slides/isection) |

### Megjegyzés

Ha egy elem már létezik ehhez a szekcióhoz a gyűjteményben, akkor a meglévő elemet adja vissza.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | A hivatkozott szekció nem tartozik az aktuális bemutatóhoz, vagy nem tartalmaz diákat. |



### Lásd még
* osztály [`ISection`](/slides/python-net/hu/aspose.slides/isection)
* osztály [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe)
* osztály [`ISummaryZoomSection`](/slides/python-net/hu/aspose.slides/isummaryzoomsection)
* osztály [`SummaryZoomSectionCollection`](/slides/python-net/hu/aspose.slides/summaryzoomsectioncollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)