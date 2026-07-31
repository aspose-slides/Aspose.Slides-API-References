---
title: get_Points()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan titik untuk IInkLine System::Drawing::PointF Hanya-baca."
type: docs
weight: 14
url: /id/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() metode

Mendapatkan titik untuk IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Hanya-baca.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Catatan

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Kelas [InkTrace](../)
* Ruang Nama [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)