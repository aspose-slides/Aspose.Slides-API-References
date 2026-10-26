---
title: get_Color()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera kolor pędzla dla linii.
type: docs
weight: 1
url: /pl/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() metoda


Pobiera kolor pędzla dla linii.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Zobacz także

* Klasa [Color](../../../system.drawing/color/)
* Klasa [InkBrush](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)