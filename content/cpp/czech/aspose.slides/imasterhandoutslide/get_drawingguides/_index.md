---
title: get_DrawingGuides()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací kolekci výkresových vodítek pro hlavní list výstupního snímku. Pouze ke čtení IDrawingGuidesCollection
type: docs
weight: 14
url: /cs/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() metoda


Vrací kolekci výkresových vodítek pro hlavní list výstupního snímku. Pouze ke čtení [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Přidání nového vodorovného výkresového vodítka nad střed snímku
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Třída [IMasterHandoutSlide](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)