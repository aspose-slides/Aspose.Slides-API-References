---
title: get_DrawingGuides()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een verzameling van tekenrichtlijnen voor de lay-outdia. Alleen-lezen IDrawingGuidesCollection
type: docs
weight: 118
url: /nl/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() methode

Retourneert een verzameling van tekenrichtlijnen voor de lay-outdia. Alleen-lezen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Opmerkingen

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Voegt de nieuwe verticale tekenrichtlijn toe links van het midden van de dia
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [LayoutSlide](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)