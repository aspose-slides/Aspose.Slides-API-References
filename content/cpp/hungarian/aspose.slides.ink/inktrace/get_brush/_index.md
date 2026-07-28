---
title: get_Brush()
second_title: Aspose.Slides C++ API referencia
description: Az IInkLine IInkBrush ecsetjét adja vissza. Csak olvasható.
type: docs
weight: 1
url: /hu/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() metódus

Az IInkLine [IInkBrush](../../iinkbrush/) ecsetjét adja vissza. Csak olvasható.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IInkBrush](../../iinkbrush/)
* Osztály [InkTrace](../)
* Névtér [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)