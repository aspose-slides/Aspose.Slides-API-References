---
title: get_DrawingGuides()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce una raccolta di guide di disegno per la diapositiva master handout. Solo lettura IDrawingGuidesCollection
type: docs
weight: 53
url: /it/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() metodo


Restituisce una raccolta di guide di disegno per la diapositiva master handout. Solo lettura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [MasterHandoutSlide](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)