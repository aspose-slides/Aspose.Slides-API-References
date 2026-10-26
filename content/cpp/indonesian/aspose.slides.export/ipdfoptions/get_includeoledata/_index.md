---
title: get_IncludeOleData()
second_title: Aspose.Slides untuk C++ Referensi API
description: True untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Baca bool.
type: docs
weight: 456
url: /id/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() metode

True to convert all OLE data from the presentation to embedded files in the resulting PDF. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

* Kelas [IPdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)