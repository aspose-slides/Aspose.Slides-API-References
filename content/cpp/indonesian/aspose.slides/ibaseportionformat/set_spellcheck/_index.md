---
title: set_SpellCheck()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks tidak dilakukan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah false.
type: docs
weight: 612
url: /id/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) metode

Mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks ditiadakan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## Catatan

Contoh berikut menunjukkan cara mengaktifkan flag SpellCheck sebelum menyimpan presentasi:

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Akses bagian teks pertama di dalam shape pertama pada slide pertama
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Aktifkan pemeriksaan ejaan untuk bagian teks ini
portion->get_PortionFormat()->set_SpellCheck(true);
// Simpan presentasi yang telah dimodifikasi
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [IBasePortionFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)