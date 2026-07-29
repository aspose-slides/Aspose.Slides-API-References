---
title: get_DrawingGuides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling ritningsguider för master notessidan. Skrivskyddad IDrawingGuidesCollection
type: docs
weight: 27
url: /sv/aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() metod


Returnerar en samling ritningsguider för master notessidan. Skrivskyddad [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klass [IMasterNotesSlide](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)