---
title: set_Size()
second_title: مرجع API Aspose.Slides برای C++
description: اندازه قلم‌مو را برای یک خط به نقطه تنظیم می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) متد

اندازه قلم‌مو را برای یک خط به نقطه تنظیم می‌کند.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
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

## همچنین ببینید

* کلاس [SizeF](../../../system.drawing/sizef/)
* کلاس [IInkBrush](../)
* فضای نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)