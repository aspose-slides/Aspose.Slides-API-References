---
title: get_Brush()
second_title: Aspose.Slides für C++ API Referenz
description: Liefert Brush für die IInkLine IInkBrush. Nur lesend.
type: docs
weight: 1
url: /de/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() Methode


Liefert den Pinsel für die IInkLine [IInkBrush](../../iinkbrush/). Nur lesend.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Hinweise


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
* Klasse [IInkTrace](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)