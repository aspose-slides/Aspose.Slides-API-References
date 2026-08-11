---
title: get_Size()
second_title: Aspose.Slides برای C++ مرجع API
description: اندازهٔ قلم‌مو را برای یک خط به واحد نقطه دریافت می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() متد

اندازهٔ قلم‌مو را برای یک خط به واحد نقطه (points) دریافت می‌کند.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## مراجع

* کلاس [SizeF](../../../system.drawing/sizef/)
* کلاس [InkBrush](../)
* فضای‌نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)