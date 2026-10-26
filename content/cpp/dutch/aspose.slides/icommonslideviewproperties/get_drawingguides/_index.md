---
title: get_DrawingGuides()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de collectie van de tekenrichtlijnen. Alleen-lezen IDrawingGuidesCollection
type: docs
weight: 53
url: /nl/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() methode


Retourneert de verzameling tekenrichtlijnen. Alleen-lezen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Opmerkingen


De volgende voorbeeldcode laat zien hoe u de nieuwe tekenrichtlijnen toevoegt aan een PowerPoint-presentatie. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Voegt de nieuwe verticale tekenrichtlijn toe aan de rechterkant van het midden van de dia
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Voegt de nieuwe horizontale tekenrichtlijn toe onder het midden van de dia
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [ICommonSlideViewProperties](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)