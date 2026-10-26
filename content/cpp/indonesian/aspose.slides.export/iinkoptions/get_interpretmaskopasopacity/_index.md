---
title: get_InterpretMaskOpAsOpacity()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggunakan operasi ROP atau Opacity untuk merender kuas.
type: docs
weight: 27
url: /id/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() method


Menggunakan operasi ROP atau Opacity untuk merender kuas.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Catatan


Nilai default adalah true. 

Contoh berikut menunjukkan cara mengatur menggunakan ROP untuk mengekspor elemen [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lihat Juga

* Kelas [IInkOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)