---
title: get_SpellCheck()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks tidak dilakukan. Ketika diatur ke true, pemeriksaan ejaan diperbolehkan. Nilai default adalah false.
type: docs
weight: 599
url: /id/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() metode


Mengembalikan nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks tidak dilakukan. Ketika diatur ke true, pemeriksaan ejaan diperbolehkan. Nilai default adalah **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Catatan


Contoh berikut menunjukkan cara mengaktifkan flag SpellCheck sebelum menyimpan presentasi: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [IBasePortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)