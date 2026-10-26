---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás segítségével
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Új Summary Zoom keretet hoz létre, és beszúrja a alakzatgyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától induló index, amelynél a Summary Zoom keretet be kell szúrni. |
| x | **float** | Az új Summary Zoom keret x koordinátája pontokban. |
| y | **float** | Az új Summary Zoom keret y koordinátája pontokban. |
| width | **float** | Az új Summary Zoom keret szélessége pontokban. |
| height | **float** | Az új Summary Zoom keret magassága pontokban. |

### Megjegyzés

Ez a metódus létrehoz egy Summary Zoom keretet, amely összegzi a bemutató összes szakaszához tartozó összegző hivatkozásokat.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a bemutató nem tartalmaz szakaszokat, vagy ha a cél diát nem egy szakaszhoz tartozik. |



### Lásd még
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* osztály [`ISummaryZoomFrame`](/slides/python-net/hu/aspose.slides/isummaryzoomframe)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)