---
title: set_Size()
second_title: Aspose.Slides C++ API referenciája
description: Beállítja a vonal ecsetméretét pontban.
type: docs
weight: 40
url: /hu/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) metódus


Beállítja a vonal ecsetméretét pontban.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
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
* Osztály [IInkBrush](../)
* Névterület [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)