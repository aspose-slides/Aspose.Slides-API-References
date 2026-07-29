---
title: get_DrawingGuides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling ritningsguider för masterbilden. Skrivskyddad IDrawingGuidesCollection
type: docs
weight: 170
url: /sv/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() metod


Returnerar en samling ritningsguider för masterbilden. Skrivskyddad [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Lägger till den nya vertikala ritningsguiden till höger om bildens centrum
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klass [MasterSlide](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)