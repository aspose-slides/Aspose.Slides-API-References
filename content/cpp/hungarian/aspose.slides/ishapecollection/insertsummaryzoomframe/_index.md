---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides C++ API referencia
description: Új Summary Zoom keretet hoz létre, és beszúrja a shape gyűjteménybe a megadott indexnél.
type: docs
weight: 157
url: /hu/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metódus


Új Summary Zoom keretet hoz létre, és beszúrja a shape gyűjteménybe a megadott indexen.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nullánál kezdődő index, amelybe be kell szúrni a Summary Zoom keretet. |
| x | **float** | Az új Summary Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Summary Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Summary Zoom keret szélessége pontban. |
| height | **float** | Az új Summary Zoom keret magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [ISummaryZoomFrame](../../isummaryzoomframe/).
## Megjegyzés


Ez a metódus egy Summary Zoom keretet hoz létre, amely összegzi az összes szekció összefoglaló hivatkozásait a bemutatóban. 

Ez a példa bemutatja egy Summary Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szekció van): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomFrame](../../isummaryzoomframe/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)