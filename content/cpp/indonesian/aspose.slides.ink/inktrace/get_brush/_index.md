---
title: get_Brush()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan Brush untuk IInkLine IInkBrush Hanya-baca.
type: docs
weight: 1
url: /id/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() metode


Mendapatkan Brush untuk IInkLine [IInkBrush](../../iinkbrush/) Hanya-baca.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IInkBrush](../../iinkbrush/)
* Kelas [InkTrace](../)
* Ruang Nama [Aspose::Slides::Ink](../../)
* Perpustakaan [Aspose.Slides](../../../)