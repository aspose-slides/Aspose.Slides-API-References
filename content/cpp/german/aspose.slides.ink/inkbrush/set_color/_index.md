---
title: set_Color()
second_title: Aspose.Slides für C++ API Referenz
description: Legt die Pinselfarbe für eine Linie fest.
type: docs
weight: 14
url: /de/aspose.slides.ink/inkbrush/set_color/
---
## InkBrush::set_Color(System::Drawing::Color) Methode

Setzt die Pinselfarbe für eine Linie.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Color(System::Drawing::Color value) override
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
* Klasse [InkBrush](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)