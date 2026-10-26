---
title: get_Traces()
second_title: Aspose.Slides C++ API Referencia
description: Az összes nyomot lekéri, amely az IInk elem IInkTrace-ban található. Csak olvasható.
type: docs
weight: 1
url: /hu/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() metódus


Az összes nyomot lekéri, amelyek a(z) [IInk](../) elem [IInkTrace](../../iinktrace/)-ban. Csak olvasható.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
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
* Osztály [IInk](../)
* Névtér [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)