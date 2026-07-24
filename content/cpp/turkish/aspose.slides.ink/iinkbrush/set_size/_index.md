---
title: set_Size()
second_title: Aspose.Slides için C++ API Referansı
description: Bir çizgi için fırça boyutunu nokta cinsinden ayarlar.
type: docs
weight: 40
url: /tr/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) metot


Bir çizgi için fırça boyutunu nokta cinsinden ayarlar.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
```

## Açıklama


Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## İlgili

* Sınıf [SizeF](../../../system.drawing/sizef/)
* Sınıf [IInkBrush](../)
* Ad alanı [Aspose::Slides::Ink](../../)
* Kütüphane [Aspose.Slides](../../../)