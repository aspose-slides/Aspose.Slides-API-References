---
title: add_summary_zoom_frame method
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Létrehoz egy új Summary Zoom keretet, és a shape gyűjtemény végére adja hozzá.

### Visszatérési érték

Az újonnan létrehozott [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Summary Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Summary Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Summary Zoom keret szélessége pontban. |
| height | **float** | Az új Summary Zoom keret magassága pontban. |

### Megjegyzések

Ez a metódus létrehoz egy új Summary Zoom-ot, és minden szekcióhoz a prezentációban egy objektumgyűjteményt helyez bele.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a prezentációban nincsenek szekciók, vagy ha a cél diák nem tartozik egy szekcióhoz sem. |



### Lásd még
* osztály [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)