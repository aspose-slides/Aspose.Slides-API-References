---
title: get_Size()
second_title: Aspose.Slides برای مرجع API C++
description: اندازهٔ براش را برای یک خط به نقطه برمی‌گرداند.
type: docs
weight: 27
url: /fa/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() متد

اندازه‌ٔ براش را برای یک خط به نقطه برمی‌گرداند.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
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

## موارد مرتبط

* کلاس [SizeF](../../../system.drawing/sizef/)
* کلاس [IInkBrush](../)
* فضای‌نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)