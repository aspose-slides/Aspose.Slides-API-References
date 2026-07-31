---
title: set_Color()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur warna kuas untuk sebuah garis.
type: docs
weight: 14
url: /id/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) metode


Mengatur warna kuas untuk sebuah garis.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Lihat Juga

* Kelas [Color](../../../system.drawing/color/)
* Kelas [IInkBrush](../)
* Ruang Nama [Aspose::Slides::Ink](../../)
* Pustaka [Aspose.Slides](../../../)