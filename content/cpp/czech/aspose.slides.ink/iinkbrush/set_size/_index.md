---
title: set_Size()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví velikost štětce pro čáru v bodech.
type: docs
weight: 40
url: /cs/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) metoda


Nastaví velikost štětce pro čáru v bodech.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
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

* třída [SizeF](../../../system.drawing/sizef/)
* třída [IInkBrush](../)
* jmenný prostor [Aspose::Slides::Ink](../../)
* knihovna [Aspose.Slides](../../../)