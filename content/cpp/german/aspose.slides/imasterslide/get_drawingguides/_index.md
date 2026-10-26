---
title: get_DrawingGuides()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. Nur-Lesen IDrawingGuidesCollection
type: docs
weight: 105
url: /de/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() Methode


Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. Nur-Lesen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Hinweise



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Hinzufügen der neuen vertikalen Zeichenhilfe rechts von der Folienmitte
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [IMasterSlide](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)