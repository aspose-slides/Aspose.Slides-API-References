---
title: get_Traces()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar alla spår som finns i IInk-elementet IInkTrace. Skrivskyddad.
type: docs
weight: 1
url: /sv/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() metod


Hämtar alla spår som finns i [IInk](../) elementet [IInkTrace](../../iinktrace/). Skrivskyddad.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IInkTrace](../../iinktrace/)
* Klass [IInk](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)