---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Új Summary Zoom keretet hoz létre, és a megadott indexnél beszúrja a shape gyűjteménybe.

### Visszatérési érték

Az újonnan létrehozott [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától számított index, amelynél a Summary Zoom keretet be kell szúrni. |
| x | **float** | Az új Summary Zoom keret x-koordinátája pontokban. |
| y | **float** | Az új Summary Zoom keret y-koordinátája pontokban. |
| width | **float** | Az új Summary Zoom keret szélessége pontokban. |
| height | **float** | Az új Summary Zoom keret magassága pontokban. |

### Megjegyzés

Ez a metódus létrehoz egy Summary Zoom keretet, amely az összes szekció összefoglaló hivatkozásait gyűjti össze a bemutatóban.

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Akkor kerül dobásra, ha a bemutató nem tartalmaz szekciókat, vagy ha a cél diák nem tartozik egy szekcióhoz sem. |



### Lásd még
* osztály [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)