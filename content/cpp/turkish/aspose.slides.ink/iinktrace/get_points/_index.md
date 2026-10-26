---
title: get_Points()
second_title: Aspose.Slides for C++ API Referansı
description: "IInkLine System::Drawing::PointF için noktaları alır. Yalnızca okuma."
type: docs
weight: 14
url: /tr/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() yöntemi


Gets points for the IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Yalnızca okuma.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Ayrıca bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [IInkTrace](../)
* Ad alanı [Aspose::Slides::Ink](../../)
* Kütüphane [Aspose.Slides](../../../)