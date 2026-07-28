---
title: get_Brush()
second_title: Aspose.Slides C++ API Referencia
description: Lekéri a Brush-et az IInkLine IInkBrush számára csak olvasható.
type: docs
weight: 1
url: /hu/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() metódus

Lekéri a Brush-t az IInkLine [IInkBrush](../../iinkbrush/) Csak olvasható.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Megjegyzések

Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IInkBrush](../../iinkbrush/)
* Osztály [IInkTrace](../)
* Névtér [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)