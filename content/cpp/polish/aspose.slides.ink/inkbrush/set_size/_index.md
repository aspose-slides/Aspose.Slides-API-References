---
title: set_Size()
second_title: Aspose.Slides – dokumentacja API C++
description: Ustawia rozmiar pędzla dla linii w punktach.
type: docs
weight: 40
url: /pl/aspose.slides.ink/inkbrush/set_size/
---
## InkBrush::set_Size(System::Drawing::SizeF) method


Ustawia rozmiar pędzla dla linii w punktach.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Size(System::Drawing::SizeF value) override
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

## Zobacz też

* Klasa [SizeF](../../../system.drawing/sizef/)
* Klasa [InkBrush](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)