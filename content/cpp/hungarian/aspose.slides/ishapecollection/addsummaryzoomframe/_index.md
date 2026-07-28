---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy új Summary Zoom keretet, és hozzáadja az alakgyűjtemény végéhez.
type: docs
weight: 144
url: /hu/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) metódus


Létrehoz egy új Summary Zoom keretet, és hozzáadja a alakgyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
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


Ez a metódus egy Summary Zoom keretet hoz létre, amely összegzi az összes szekció összefoglaló hivatkozásait a prezentációban. 

Ez a példa bemutatja, hogyan adhatunk egy Summary Zoom objektumot a gyűjtemény végéhez (feltételezve, hogy a „Presentation.pptx” prezentációban legalább két szekció van): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomFrame](../../isummaryzoomframe/)
* Osztály [IShapeCollection](../)
* Névterület [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)