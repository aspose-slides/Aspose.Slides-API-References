---
title: get_Brush()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على Brush للـ IInkLine IInkBrush قراءة فقط.
type: docs
weight: 1
url: /ar/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() طريقة


يحصل على Brush للـ IInkLine [IInkBrush](../../iinkbrush/) قراءة فقط.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IInkBrush](../../iinkbrush/)
* فئة [IInkTrace](../)
* نطاق [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)