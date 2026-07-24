---
title: get_DrawingGuides()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sammlung der Zeichenhilfen zurück. Nur-Lesen IDrawingGuidesCollection
type: docs
weight: 53
url: /de/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() Methode


Gibt die Sammlung der Zeichenhilfen zurück. Nur-Lesen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Hinweise


Der folgende Beispielcode zeigt, wie Sie die neuen Zeichenhilfen in einer PowerPoint-Präsentation hinzufügen.
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

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [ICommonSlideViewProperties](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)