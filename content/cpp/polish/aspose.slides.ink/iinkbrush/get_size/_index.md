---
title: get_Size()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca rozmiar pędzla dla linii w punktach.
type: docs
weight: 27
url: /pl/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() metoda

Zwraca rozmiar pędzla dla linii w punktach.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Zobacz także

* Klasa [SizeF](../../../system.drawing/sizef/)
* Klasa [IInkBrush](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)