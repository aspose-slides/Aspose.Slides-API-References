---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of drawing guides for the master slide. Read-only IDrawingGuidesCollection
type: docs
weight: 105
url: /aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() method


Returns a collection of drawing guides for the master slide. Read-only [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Adding the new vertical drawing guide to the right of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [IMasterSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)