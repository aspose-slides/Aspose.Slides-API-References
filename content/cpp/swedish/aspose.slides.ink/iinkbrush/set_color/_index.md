---
title: set_Color()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in penselfärgen för en linje.
type: docs
weight: 14
url: /sv/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) metod


Ställer in penselfärgen för en linje.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Se även

* Klass [Color](../../../system.drawing/color/)
* Klass [IInkBrush](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Bibliotek [Aspose.Slides](../../../)