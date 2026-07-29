---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt Summary Zoom-ram och infogar det i shape collection på det angivna indexet.
type: docs
weight: 170
url: /sv/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metod

Skapar ett nytt Summary Zoom frame och infogar det i shape collection på det angivna indexet.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där Summary Zoom frame ska infogas. |
| x | **float** | x-koordinaten för den nya Summary Zoom frame, i punkter. |
| y | **float** | y-koordinaten för den nya Summary Zoom frame, i punkter. |
| width | **float** | Bredden på den nya Summary Zoom frame, i punkter. |
| height | **float** | Höjden på den nya Summary Zoom frame, i punkter. |

### Returvärde

Den nyss skapade [ISummaryZoomFrame](../../isummaryzoomframe/).
## Anmärkningar

Denna metod skapar ett Summary Zoom frame som samlar samman länkar för alla avsnitt i presentationen. 

Detta exempel demonstrerar hur man skapar och infogar ett Summary Zoom-objekt på det angivna indexet i en samling (anta att det finns minst två avsnitt i presentationen \"Presentation.pptx\"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)