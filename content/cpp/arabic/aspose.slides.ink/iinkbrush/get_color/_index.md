---
title: get_Color()
second_title: Aspose.Slides لمرجع API للـ C++
description: يحصل على لون الفرشاة لخط.
type: docs
weight: 1
url: /ar/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() طريقة


يحصل على لون الفرشاة لخط.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
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

* الفئة [Color](../../../system.drawing/color/)
* الفئة [IInkBrush](../)
* النطاق [Aspose::Slides::Ink](../../)
* المكتبة [Aspose.Slides](../../../)