---
title: set_IncludeOleData()
second_title: Referensi API Aspose.Slides untuk C++
description: Benar untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Tulis bool.
type: docs
weight: 469
url: /id/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) metode


Benar untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Tulis **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Catatan


Bawaan adalah **false**.

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Lihat Juga

* Kelas [PdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)