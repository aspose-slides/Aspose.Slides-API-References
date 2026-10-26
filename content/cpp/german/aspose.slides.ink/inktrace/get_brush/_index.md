---
title: get_Brush()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Brush für die IInkLine IInkBrush zurück. Nur lesbar.
type: docs
weight: 1
url: /de/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() Methode


Gibt den Brush für die IInkLine [IInkBrush](../../iinkbrush/) zurück. Nur lesbar.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Anmerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInkBrush](../../iinkbrush/)
* Klasse [InkTrace](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)