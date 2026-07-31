---
title: get_Traces()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil semua jejak yang terdapat dalam elemen IInk IInkTrace. Baca-saja.
type: docs
weight: 1
url: /id/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() metode


Mengambil semua jejak yang terdapat dalam elemen [IInk](../) [IInkTrace](../../iinktrace/). Baca-saja.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
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
* Kelas [IInk](../)
* Ruang Nama [Aspose::Slides::Ink](../../)
* Perpustakaan [Aspose.Slides](../../../)