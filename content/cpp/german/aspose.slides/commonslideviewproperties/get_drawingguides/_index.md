---
title: get_DrawingGuides()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sammlung der Zeichenhilfen zurück. Schreibgeschützt IDrawingGuidesCollection
type: docs
weight: 53
url: /de/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() method

Gibt die Sammlung der Zeichenhilfen zurück. Schreibgeschützt [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Bemerkungen

Der folgende Beispielcode zeigt, wie neue Zeichenhilfen zu einer PowerPoint-Präsentation hinzugefügt werden können. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Adding the new vertical drawing guide to the right of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [CommonSlideViewProperties](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)