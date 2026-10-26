---
title: get_Size()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan ukuran kuas untuk garis dalam poin.
type: docs
weight: 27
url: /id/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() metode

Mendapatkan ukuran kuas untuk garis dalam poin.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
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
* Ruang nama [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)