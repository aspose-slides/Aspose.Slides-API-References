---
title: get_DrawingGuides()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací kolekci výkresových vodítek. Pouze ke čtení IDrawingGuidesCollection
type: docs
weight: 53
url: /cs/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() metoda

Vrací kolekci výkresových vodítek. Pouze ke čtení [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Poznámky

Následující ukázkový kód ukazuje, jak přidat nové výkresové vodítka do prezentace PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Přidání nového vertikálního vodítka vpravo od středu snímku
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Přidání nového horizontálního vodítka pod střed snímku
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [CommonSlideViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)