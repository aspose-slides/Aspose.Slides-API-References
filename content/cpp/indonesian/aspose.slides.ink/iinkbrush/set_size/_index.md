---
title: set_Size()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur ukuran kuas untuk sebuah garis dalam poin.
type: docs
weight: 40
url: /id/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) metode

Mengatur ukuran kuas untuk sebuah garis dalam poin.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
```

## Catatan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Lihat Juga

* Kelas [SizeF](../../../system.drawing/sizef/)
* Kelas [IInkBrush](../)
* Ruang Nama [Aspose::Slides::Ink](../../)
* Perpustakaan [Aspose.Slides](../../../)