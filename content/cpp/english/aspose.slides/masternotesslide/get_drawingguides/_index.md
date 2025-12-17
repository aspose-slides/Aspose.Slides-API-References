---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of drawing guides for the master notes slide. Read-only IDrawingGuidesCollection
type: docs
weight: 66
url: /aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() method


Returns a collection of drawing guides for the master notes slide. Read-only [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [MasterNotesSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)