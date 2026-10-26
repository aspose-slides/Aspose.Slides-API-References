---
title: get_DrawingGuides()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vrací kolekci kreslicích vodítek pro hlavní snímek. Pouze pro čtení IDrawingGuidesCollection
type: docs
weight: 170
url: /cs/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() metoda

Vrací kolekci kreslicích vodítek pro hlavní snímek. Pouze pro čtení [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Přidání nového vertikálního kreslicího vodítka vpravo od středu snímku
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IDrawingGuidesCollection](../../idrawingguidescollection/)
* třída [MasterSlide](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)