---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of drawing guides for the master handout slide. Read-only IDrawingGuidesCollection
type: docs
weight: 53
url: /aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() method


Returns a collection of drawing guides for the master handout slide. Read-only [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [MasterHandoutSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)