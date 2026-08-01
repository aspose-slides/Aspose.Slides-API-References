---
title: get_DrawingGuides()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de collectie van de tekenlijnen. Alleen-lezen IDrawingGuidesCollection
type: docs
weight: 53
url: /nl/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() methode


Retourneert de verzameling van de tekenlijnen. Alleen-lezen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Opmerkingen


De volgende voorbeeldcode laat zien hoe u nieuwe tekenlijnen kunt toevoegen in een PowerPoint-presentatie. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Voegt de nieuwe verticale tekenlijn toe rechts van het midden van de dia
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Voegt de nieuwe horizontale tekenlijn toe onder het midden van de dia
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [CommonSlideViewProperties](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)