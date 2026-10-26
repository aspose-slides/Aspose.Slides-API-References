---
title: get_Size()
second_title: Aspose.Slides C++ API Referansı
description: Bir satır için fırça boyutunu nokta cinsinden alır.
type: docs
weight: 27
url: /tr/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() metodu


Bir satır için fırça boyutunu nokta cinsinden alır.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Ayrıca Bakınız

* Sınıf [SizeF](../../../system.drawing/sizef/)
* Sınıf [InkBrush](../)
* Ad alanı [Aspose::Slides::Ink](../../)
* Kütüphane [Aspose.Slides](../../../)