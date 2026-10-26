---
title: get_Size()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar penselns storlek för en linje i punkter.
type: docs
weight: 27
url: /sv/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() metod


Hämtar penselns storlek för en linje i punkter.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Se även

* Klass [SizeF](../../../system.drawing/sizef/)
* Klass [InkBrush](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Bibliotek [Aspose.Slides](../../../)