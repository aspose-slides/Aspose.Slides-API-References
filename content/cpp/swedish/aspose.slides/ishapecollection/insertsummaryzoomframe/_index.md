---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Summary Zoom-ram och infogar den i shape-samlingen på det angivna indexet.
type: docs
weight: 157
url: /sv/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method


Skapar en ny Summary Zoom-ram och infogar den i shape-samlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där Summary Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Summary Zoom-ramen, i punkt. |
| y | **float** | Y-koordinaten för den nya Summary Zoom-ramen, i punkt. |
| width | **float** | Bredden på den nya Summary Zoom-ramen, i punkt. |
| height | **float** | Höjden på den nya Summary Zoom-ramen, i punkt. |

### Return Value

Den nyss skapade [ISummaryZoomFrame](../../isummaryzoomframe/).
## Remarks


Denna metod skapar en Summary Zoom-ram som samlar samman länkar för alla sektioner i presentationen. 

Detta exempel demonstrerar skapande och infogning av ett Summary Zoom-objekt på det angivna indexet i en samling (förutsätt att det finns minst två sektioner i presentationen "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)