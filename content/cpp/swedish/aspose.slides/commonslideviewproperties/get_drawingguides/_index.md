---
title: get_DrawingGuides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar samlingen av ritningsguiderna. Skrivskyddad IDrawingGuidesCollection
type: docs
weight: 53
url: /sv/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() metod

Returnerar samlingen av ritningsguiderna. Skrivskyddad [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Anmärkningar

Följande exempelprogram visar hur man lägger till de nya ritningsguiderna i en PowerPoint-presentation.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Adding the new vertical drawing guide to the right of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klass [CommonSlideViewProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)