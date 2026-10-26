---
title: get_Color()
second_title: Aspose.Slides pro referenci API C++
description: Získá barvu štětce pro čáru.
type: docs
weight: 1
url: /cs/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() metoda

Získá barvu štětce pro čáru.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
```

## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Viz také

* Třída [Color](../../../system.drawing/color/)
* Třída [InkBrush](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)