---
title: get_Traces()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على جميع العلامات المتضمنة في عنصر IInk وهو IInkTrace. للقراءة فقط.
type: docs
weight: 1
url: /ar/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() طريقة

يحصل على جميع العلامات المتضمنة في عنصر [IInk](../) [IInkTrace](../../iinktrace/). للقراءة فقط.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## ملاحظات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IInkTrace](../../iinktrace/)
* فئة [IInk](../)
* مساحة الاسم [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)