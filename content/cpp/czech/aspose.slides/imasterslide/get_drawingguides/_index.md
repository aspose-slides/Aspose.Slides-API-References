---
title: get_DrawingGuides()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací kolekci kreslicích vodítek pro hlavní snímek. Pouze pro čtení IDrawingGuidesCollection
type: docs
weight: 105
url: /cs/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() metoda


Vrací kolekci kreslicích vodítek pro hlavní snímek. Pouze pro čtení [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Přidání nového svislého kreslicího vodítka napravo od středu snímku
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [IMasterSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)