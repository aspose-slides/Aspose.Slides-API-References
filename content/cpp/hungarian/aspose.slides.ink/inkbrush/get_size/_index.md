---
title: get_Size()
second_title: Aspose.Slides for C++ API Referencia
description: Lekéri a vonal ecsetméretét pontokban.
type: docs
weight: 27
url: /hu/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() metódus

Lekéri a vonal ecsetméretét pontokban.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## Megjegyzések

Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Lásd még

* Osztály [SizeF](../../../system.drawing/sizef/)
* Osztály [InkBrush](../)
* Névtér [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)