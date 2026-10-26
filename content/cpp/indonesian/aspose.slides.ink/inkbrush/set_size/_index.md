---
title: set_Size()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengatur ukuran kuas untuk sebuah garis dalam poin.
type: docs
weight: 40
url: /id/aspose.slides.ink/inkbrush/set_size/
---
## InkBrush::set_Size(System::Drawing::SizeF) metode


Mengatur ukuran kuas untuk sebuah garis dalam poin.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Size(System::Drawing::SizeF value) override
```

## Keterangan


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
* Kelas [InkBrush](../)
* Ruang Nama [Aspose::Slides::Ink](../../)
* Perpustakaan [Aspose.Slides](../../../)