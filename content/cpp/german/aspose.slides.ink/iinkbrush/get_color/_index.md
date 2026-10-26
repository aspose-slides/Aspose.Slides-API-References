---
title: get_Color()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Pinselfarbe für eine Linie.
type: docs
weight: 1
url: /de/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() Methode


Ermittelt die Pinselfarbe für eine Linie.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Siehe auch

* Klasse [Color](../../../system.drawing/color/)
* Klasse [IInkBrush](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)