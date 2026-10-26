---
title: set_HideInk()
second_title: Referensi API Aspose.Slides untuk C++
description: Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor.
type: docs
weight: 14
url: /id/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) metode

Menampilkan atau menyembunyikan [Ink](../../../aspose.slides.ink/) elemen dalam dokumen yang diekspor.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Catatan

Nilai default adalah false. 

Contoh berikut menunjukkan cara menyembunyikan [Ink](../../../aspose.slides.ink/) elemen dalam dokumen PDF yang diekspor: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lihat Juga

* Kelas [InkOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)