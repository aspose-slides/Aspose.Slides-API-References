---
title: set_Size()
second_title: Aspose.Slides for C++ API Referansı
description: Bir çizgi için fırça boyutunu nokta biriminde ayarlar.
type: docs
weight: 40
url: /tr/aspose.slides.ink/inkbrush/set_size/
---
## InkBrush::set_Size(System::Drawing::SizeF) metod

Bir çizgi için fırça boyutunu nokta biriminde ayarlar.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Size(System::Drawing::SizeF value) override
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

## Bakınız

* Sınıf [SizeF](../../../system.drawing/sizef/)
* Sınıf [InkBrush](../)
* AdAlanı [Aspose::Slides::Ink](../../)
* Kütüphane [Aspose.Slides](../../../)