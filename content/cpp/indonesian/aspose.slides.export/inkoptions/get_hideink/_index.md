---
title: get_HideInk()
second_title: Referensi API Aspose.Slides untuk C++
description: Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor.
type: docs
weight: 1
url: /id/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() metode


Menampilkan atau menyembunyikan elemen [Ink](../../../aspose.slides.ink/) dalam dokumen yang diekspor.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Keterangan


Nilai default adalah false. 

Contoh berikut menunjukkan cara menyembunyikan elemen [Ink](../../../aspose.slides.ink/) dalam dokumen PDF yang diekspor: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lihat Juga

* Kelas [InkOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)