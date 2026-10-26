---
title: get_Color()
second_title: مرجع API برای Aspose.Slides در C++
description: رنگ قلم‌مو را برای یک خط دریافت می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() متد


رنگ قلم‌مو را برای یک خط دریافت می‌کند.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## موارد مرتبط

* کلاس [Color](../../../system.drawing/color/)
* کلاس [IInkBrush](../)
* فضای نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)