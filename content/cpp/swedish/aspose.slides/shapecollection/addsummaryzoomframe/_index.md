---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Summary Zoom-ram och lägger till den i slutet av formsamlingen.
type: docs
weight: 157
url: /sv/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) metod


Skapar en ny Summary Zoom-ram och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Summary Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Summary Zoom-ramen, i punkter. |

### Returvärde

Den nyss skapade [ISummaryZoomFrame](../../isummaryzoomframe/).

## Anmärkningar


Denna metod skapar en ny Summary Zoom och placerar en samling objekt i den för alla avsnitt i den här presentationen. 

Detta exempel visar hur man lägger till ett Summary Zoom-objekt i slutet av en samling (anta att det finns minst två avsnitt i presentationen "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)