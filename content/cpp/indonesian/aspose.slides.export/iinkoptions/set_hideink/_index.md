---
title: set_HideInk()
second_title: Referensi API Aspose.Slides untuk C++
description: Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor.
type: docs
weight: 14
url: /id/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) metode


Menampilkan atau menyembunyikan elemen [Ink](../../../aspose.slides.ink/) dalam dokumen yang diekspor.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
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
* Pustaka [Aspose.Slides](../../../)