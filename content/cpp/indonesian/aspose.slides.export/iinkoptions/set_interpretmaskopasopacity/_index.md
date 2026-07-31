---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides untuk Referensi API C++
description: Menggunakan operasi ROP atau Opacity untuk merender kuas.
type: docs
weight: 40
url: /id/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) metode


Menggunakan operasi ROP atau Opacity untuk merender kuas.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Keterangan


Nilai default adalah true. 

Contoh berikut menunjukkan cara menyetel menggunakan ROP untuk mengekspor elemen [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lihat Juga

* Kelas [IInkOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)