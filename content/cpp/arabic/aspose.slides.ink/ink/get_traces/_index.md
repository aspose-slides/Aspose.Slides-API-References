---
title: get_Traces()
second_title: مرجع API Aspose.Slides للغة C++
description: يجلب جميع الآثار الموجودة في عنصر IInk IInkTrace. للقراءة فقط.
type: docs
weight: 1
url: /ar/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() طريقة


يجلب جميع الآثار الموجودة في العنصر [IInk](../../iink/) [IInkTrace](../../iinktrace/). للقراءة فقط.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IInkTrace](../../iinktrace/)
* الفئة [Ink](../)
* النطاق [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)