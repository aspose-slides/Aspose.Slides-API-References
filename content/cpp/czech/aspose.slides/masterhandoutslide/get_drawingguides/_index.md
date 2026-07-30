---
title: get_DrawingGuides()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací kolekci vodicích čar pro hlavní snímek výstřižků. Pouze pro čtení IDrawingGuidesCollection
type: docs
weight: 53
url: /cs/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() method


Vrací kolekci vodicích čar pro hlavní snímek výstřižků. Pouze pro čtení [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Přidání nové vodorovné vodící čáry nad středem snímku
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Třída [MasterHandoutSlide](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)