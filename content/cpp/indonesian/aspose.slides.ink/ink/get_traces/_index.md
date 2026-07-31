---
title: get_Traces()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan semua jejak yang terdapat dalam elemen IInk IInkTrace. Hanya-baca.
type: docs
weight: 1
url: /id/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() metode

Mendapatkan semua jejak yang terdapat dalam elemen [IInk](../../iink/) [IInkTrace](../../iinktrace/). Hanya-baca.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Catatan

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IInkTrace](../../iinktrace/)
* Kelas [Ink](../)
* RuangNama [Aspose::Slides::Ink](../../)
* Perpustakaan [Aspose.Slides](../../../)