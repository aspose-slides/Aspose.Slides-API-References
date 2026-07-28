---
title: get_Traces()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja az összes nyomot, amely az IInk elem IInkTrace-ében található. Csak olvasható.
type: docs
weight: 1
url: /hu/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() method

Visszaadja az összes nyomot, amely a [IInk](../../iink/) elem [IInkTrace](../../iinktrace/)-ben található. Csak olvasható.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IInkTrace](../../iinktrace/)
* Osztály [Ink](../)
* Névtér [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)