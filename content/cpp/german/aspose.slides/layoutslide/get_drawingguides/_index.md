---
title: get_DrawingGuides()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Sammlung von Zeichenhilfen für die Layoutfolie zurück. Schreibgeschützt IDrawingGuidesCollection
type: docs
weight: 118
url: /de/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() Methode


Gibt eine Sammlung von Zeichenhilfen für die Layoutfolie zurück. Schreibgeschützt [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Hinweise



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Hinzufügen der neuen vertikalen Zeichenhilfe links von der Folienmitte
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [LayoutSlide](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)