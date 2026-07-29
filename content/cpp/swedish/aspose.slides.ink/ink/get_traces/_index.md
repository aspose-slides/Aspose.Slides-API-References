---
title: get_Traces()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar alla spår som finns i IInk-elementet IInkTrace. Skrivskyddad.
type: docs
weight: 1
url: /sv/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() metod


Hämtar alla spår som finns i [IInk](../../iink/) elementet [IInkTrace](../../iinktrace/). Skrivskyddad.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IInkTrace](../../iinktrace/)
* Klass [Ink](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Bibliotek [Aspose.Slides](../../../)