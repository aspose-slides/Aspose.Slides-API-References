---
title: get_Traces()
second_title: Aspose.Slides için C++ API Referansı
description: IInk öğesi IInkTrace içinde bulunan tüm izleri alır. Salt okunur.
type: docs
weight: 1
url: /tr/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() metodu


[IInk](../../iink/) element [IInkTrace](../../iinktrace/) içinde bulunan tüm izleri alır. Salt okunur.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInkTrace](../../iinktrace/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)