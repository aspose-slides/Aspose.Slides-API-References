---
title: get_Size()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يسترجع حجم الفرشاة لخط بالنقاط.
type: docs
weight: 27
url: /ar/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() طريقة


يسترجع حجم الفرشاة لخط بالنقاط.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
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

* فئة [SizeF](../../../system.drawing/sizef/)
* فئة [IInkBrush](../)
* نطاق [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)