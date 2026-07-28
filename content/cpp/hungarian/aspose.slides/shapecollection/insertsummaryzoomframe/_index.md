---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides C++ API referencia
description: Új Summary Zoom keretet hoz létre, és a shape collection-be a megadott indexnél illeszti be.
type: docs
weight: 170
url: /hu/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metódus


Új Summary Zoom keretet hoz létre, és beilleszti a ShapeCollection-be a megadott indexen.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla-alapú index, amelynél a Summary Zoom keretet be kell illeszteni. |
| x | **float** | Az új Summary Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Summary Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Summary Zoom keret szélessége pontban. |
| height | **float** | Az új Summary Zoom keret magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [ISummaryZoomFrame](../../isummaryzoomframe/).

## Megjegyzések


Ez a metódus egy Summary Zoom keretet hoz létre, amely összegzi a prezentáció összes szekciójának összefoglaló hivatkozásait. 

Ez a példa bemutatja egy Summary Zoom objektum létrehozását és beillesztését a gyűjtemény a megadott indexén (feltételezve, hogy a \"Presentation.pptx\" prezentációban legalább két szekció van):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomFrame](../../isummaryzoomframe/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)