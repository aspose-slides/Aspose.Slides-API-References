---
title: get_DrawingGuides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling ritningsguider för masteranteckningsbilden. Skrivskyddad IDrawingGuidesCollection
type: docs
weight: 66
url: /sv/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() metod


Returnerar en samling ritningsguider för masteranteckningsbilden. Skrivskyddad [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
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
* Klass [MasterNotesSlide](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)