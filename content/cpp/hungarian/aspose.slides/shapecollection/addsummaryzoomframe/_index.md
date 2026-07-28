---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides C++ API hivatkozás
description: Új Summary Zoom keretet hoz létre, és az alakzatgyűjtemény végére adja hozzá.
type: docs
weight: 157
url: /hu/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) metódus


Új Summary Zoom keretet hoz létre, és az alakzatgyűjtemény végére adja hozzá.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új Summary Zoom keret x-koordinátája pontokban. |
| y | **float** | Az új Summary Zoom keret y-koordinátája pontokban. |
| width | **float** | Az új Summary Zoom keret szélessége pontokban. |
| height | **float** | Az új Summary Zoom keret magassága pontokban. |

### Visszatérési érték

Az újonnan létrehozott [ISummaryZoomFrame](../../isummaryzoomframe/).

## Megjegyzések

Ez a metódus új Summary Zoom-ot hoz létre, és a prezentáció összes szekciójába egy objektumgyűjteményt helyez bele. 

Ez a példa bemutatja, hogyan adunk egy Summary Zoom objektumot egy gyűjtemény végéhez (tételezzük fel, hogy a "Presentation.pptx" prezentációban legalább két szekció van):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)