---
title: get_Color()
second_title: Aspose.Slides için C++ API Referansı
description: Bir satır için fırça rengini alır.
type: docs
weight: 1
url: /tr/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() metod


Bir satır için fırça rengini alır.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
```

## Açıklamalar


Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## İlgili

* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [IInkBrush](../)
* Ad alanı [Aspose::Slides::Ink](../../)
* Kütüphane [Aspose.Slides](../../../)