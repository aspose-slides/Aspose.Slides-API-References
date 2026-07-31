---
title: get_HideInk()
second_title: Referensi API Aspose.Slides untuk C++
description: Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor.
type: docs
weight: 1
url: /id/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() metode


Menampilkan atau menyembunyikan elemen [Ink](../../../aspose.slides.ink/) dalam dokumen yang diekspor.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Catatan


Nilai default adalah false. 

Contoh berikut menunjukkan cara menyembunyikan elemen [Ink](../../../aspose.slides.ink/) dalam dokumen PDF yang diekspor: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lihat Juga

* Kelas [IInkOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)