---
title: get_DrawingGuides()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een collectie van tekenrichtlijnen voor de masterdia. Alleen-lezen IDrawingGuidesCollection
type: docs
weight: 105
url: /nl/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() methode


Retourneert een collectie van tekenrichtlijnen voor de masterdia. Alleen-lezen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Voegt de nieuwe verticale tekenrichtlijn toe aan de rechterkant van het midden van de dia
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [IMasterSlide](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)