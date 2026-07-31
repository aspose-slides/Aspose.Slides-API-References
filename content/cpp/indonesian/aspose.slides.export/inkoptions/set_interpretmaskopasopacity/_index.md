---
title: set_InterpretMaskOpAsOpacity()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggunakan operasi ROP atau Opacity untuk merender kuas.
type: docs
weight: 40
url: /id/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) metode


Menggunakan operasi ROP atau Opacity untuk merender kuas.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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

* Kelas [InkOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)