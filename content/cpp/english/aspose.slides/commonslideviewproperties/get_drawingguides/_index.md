---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Reference
description: Returns the collection of the drawing guides. Read-only IDrawingGuidesCollection
type: docs
weight: 53
url: /aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() method


Returns the collection of the drawing guides. Read-only [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Remarks


The following sample code shows how to add the new drawing guides in a PowerPoint presentation. 
```cpp
[C#]
using (Presentation pres = new Presentation())
{
    var slideSize = pres.SlideSize.Size;

    IDrawingGuidesCollection guides = pres.ViewProperties.SlideViewProperties.DrawingGuides;
    // Adding the new vertical drawing guide to the right of the slide center
    guides.Add(Orientation.Vertical, slideSize.Width / 2 + 12.5f);
    // Adding the new horizontal drawing guide below the slide center
    guides.Add(Orientation.Horizontal, slideSize.Height / 2 + 12.5f);

    pres.Save("DrawingGuides_out.pptx", SaveFormat.Pptx);
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [CommonSlideViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)