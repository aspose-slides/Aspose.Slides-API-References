---
title: get_Size()
second_title: Aspose.Slides pro C++ API Reference
description: Získá velikost štětce pro čáru v bodech.
type: docs
weight: 27
url: /cs/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() metoda


Získá velikost štětce pro čáru v bodech.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Viz také

* Třída [SizeF](../../../system.drawing/sizef/)
* Třída [InkBrush](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)