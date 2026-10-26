---
title: get_DrawingGuides()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Sammlung von Zeichenhilfen für die Layout-Folien zurück. Nur lesbar IDrawingGuidesCollection
type: docs
weight: 79
url: /de/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() Methode


Gibt eine Sammlung von Zeichenhilfen für die Layout-Folien zurück. Nur lesbar [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## Bemerkungen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Hinzufügen der neuen vertikalen Zeichenhilfe links vom Folienzentrum
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [ILayoutSlide](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)