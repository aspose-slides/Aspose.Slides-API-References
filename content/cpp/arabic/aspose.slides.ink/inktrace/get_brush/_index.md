---
title: get_Brush()
second_title: Aspose.Slides لمرجع API C++
description: يسترجع Brush للـ IInkLine IInkBrush للقراءة فقط.
type: docs
weight: 1
url: /ar/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() طريقة

يسترجع Brush للـ IInkLine [IInkBrush](../../iinkbrush/) للقراءة فقط.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
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

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IInkBrush](../../iinkbrush/)
* فئة [InkTrace](../)
* نطاق [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)