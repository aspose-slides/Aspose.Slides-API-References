---
title: get_IncludeOleData()
second_title: Referensi API Aspose.Slides untuk C++
description: True untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Baca bool.
type: docs
weight: 456
url: /id/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() metode

True untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Baca **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Catatan

Default adalah **false**. 

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
* Perpustakaan [Aspose.Slides](../../../)