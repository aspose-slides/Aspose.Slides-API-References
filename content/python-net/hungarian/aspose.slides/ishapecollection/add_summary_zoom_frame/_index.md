---
title: add_summary_zoom_frame method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Új Summary Zoom keretet hoz létre, és hozzáadja a alakzatgyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe).

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Az új Summary Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Summary Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Summary Zoom keret szélessége pontban. |
| height | **float** | Az új Summary Zoom keret magassága pontban. |

### Megjegyzés

Ez a metódus egy Summary Zoom keretet hoz létre, amely összegzi a bemutató összes szakaszának összefoglaló hivatkozásait.

### Kivételek

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a bemutatóban nincsenek szakaszok, vagy ha a cél dia nem tartozik egy szakaszhoz sem. |

### Lásd még
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* osztály [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)