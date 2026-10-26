---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Summary Zoom-ram och lägger till den i slutet av shape collection.
type: docs
weight: 144
url: /sv/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) metod

Skapar en ny Summary Zoom-ram och lägger till den i slutet av shape collection.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Summary Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Summary Zoom-ramen, i punkter. |

### Returvärde

Den nyss skapade [ISummaryZoomFrame](../../isummaryzoomframe/).
## Anmärkningar

Denna metod skapar en Summary Zoom-ram som samlar samman övergripande länkar för alla sektioner i presentationen.

Detta exempel demonstrerar hur man lägger till ett Summary Zoom-objekt i slutet av en samling (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)