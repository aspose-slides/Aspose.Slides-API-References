---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of drawing guides for the layout slide. Read-only IDrawingGuidesCollection
type: docs
weight: 118
url: /aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() method


Returns a collection of drawing guides for the layout slide. Read-only [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Adding the new vertical drawing guide to the left of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [LayoutSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)