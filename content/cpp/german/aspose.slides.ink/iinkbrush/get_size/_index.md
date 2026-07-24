---
title: get_Size()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt die Pinselgröße für eine Linie in Punkten zurück.
type: docs
weight: 27
url: /de/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() Methode


Gibt die Pinselgröße für eine Linie in Punkten zurück.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
```

## Anmerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Siehe auch

* Klasse [SizeF](../../../system.drawing/sizef/)
* Klasse [IInkBrush](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)