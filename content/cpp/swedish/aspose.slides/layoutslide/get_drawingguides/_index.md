---
title: get_DrawingGuides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling ritguider för layout-bilden. Skrivskyddad IDrawingGuidesCollection
type: docs
weight: 118
url: /sv/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() metod


Returnerar en samling ritguider för layout-bilden. Skrivskyddad [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Lägger till den nya vertikala ritguiden åt vänster om bildens centrum
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klass [LayoutSlide](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)