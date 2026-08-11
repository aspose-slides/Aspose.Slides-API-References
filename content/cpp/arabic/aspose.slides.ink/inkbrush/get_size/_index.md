---
title: get_Size()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على حجم الفرشاة لخط في النقاط.
type: docs
weight: 27
url: /ar/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() طريقة

يحصل على حجم الفرشاة لخط في النقاط.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## انظر أيضًا

* الفئة [SizeF](../../../system.drawing/sizef/)
* الفئة [InkBrush](../)
* النطاق [Aspose::Slides::Ink](../../)
* المكتبة [Aspose.Slides](../../../)