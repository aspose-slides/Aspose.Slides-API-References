---
title: get_Points()
second_title: Aspose.Slides for C++ API Referansı
description: "IInkLine için System::Drawing::PointF noktalarını alır. Yalnızca okunabilir."
type: docs
weight: 14
url: /tr/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() metod

IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) için noktaları alır. Yalnızca okunabilir.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Bkz

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [InkTrace](../)
* AdAlanı [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)