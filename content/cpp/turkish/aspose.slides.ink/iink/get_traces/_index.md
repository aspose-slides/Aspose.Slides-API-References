---
title: get_Traces()
second_title: Aspose.Slides for C++ API Referansı
description: IInk öğesindeki IInkTrace içinde bulunan tüm izleri alır. Yalnızca okuma.
type: docs
weight: 1
url: /tr/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() yöntemi

[IInk](../) öğesindeki [IInkTrace](../../iinktrace/) içinde bulunan tüm izleri alır. Yalnızca okuma.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Açıklama

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IInkTrace](../../iinktrace/)
* Sınıf [IInk](../)
* Ad Alanı [Aspose::Slides::Ink](../../)
* Kütüphane [Aspose.Slides](../../../)