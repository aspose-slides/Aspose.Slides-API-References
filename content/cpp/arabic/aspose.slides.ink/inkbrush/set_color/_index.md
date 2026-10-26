---
title: set_Color()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يضبط لون الفرشاة لخط.
type: docs
weight: 14
url: /ar/aspose.slides.ink/inkbrush/set_color/
---
## InkBrush::set_Color(System::Drawing::Color) طريقة

يضبط لون الفرشاة لخط.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Color(System::Drawing::Color value) override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## انظر أيضًا

* فئة [Color](../../../system.drawing/color/)
* فئة [InkBrush](../)
* نطاق [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)