---
title: get_DrawingGuides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling ritningsguider för layoutbilden. Skrivskyddad IDrawingGuidesCollection
type: docs
weight: 79
url: /sv/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() metod


Returnerar en samling ritningsguider för layoutbilden. Skrivskyddad [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Lägger till den nya vertikala ritningsguiden till vänster om bildens mitt
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IDrawingGuidesCollection](../../idrawingguidescollection/)
* klass [ILayoutSlide](../)
* namnutrymme [Aspose::Slides](../../)
* bibliotek [Aspose.Slides](../../../)