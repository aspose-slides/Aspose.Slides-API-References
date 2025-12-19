---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of drawing guides for the master notes slide. Read-only IDrawingGuidesCollection
type: docs
weight: 27
url: /aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() method


Returns a collection of drawing guides for the master notes slide. Read-only [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
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
* Class [IMasterNotesSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)