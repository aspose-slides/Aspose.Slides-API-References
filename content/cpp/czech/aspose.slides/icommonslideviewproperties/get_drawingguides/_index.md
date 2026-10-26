---
title: get_DrawingGuides()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací kolekci kreslicích vodítek. Pouze ke čtení IDrawingGuidesCollection
type: docs
weight: 53
url: /cs/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() metoda

Vrací kolekci kreslicích vodítek. Pouze ke čtení [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Poznámky

Následující ukázkový kód ukazuje, jak přidat nová kreslicí vodítka do prezentace PowerPoint. ```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Přidání nového vertikálního kreslicího vodítka napravo od středu snímku
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Přidání nového horizontálního kreslicího vodítka pod střed snímku
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Třída [ICommonSlideViewProperties](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)