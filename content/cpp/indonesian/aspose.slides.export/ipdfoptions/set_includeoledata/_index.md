---
title: set_IncludeOleData()
second_title: Aspose.Slides untuk Referensi API C++
description: True untuk mengonversi semua data OLE dari presentasi menjadi file tertanam dalam PDF yang dihasilkan. Tulis **bool**.
type: docs
weight: 469
url: /id/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) metode


True untuk mengonversi semua data OLE dari presentasi menjadi file tertanam dalam PDF yang dihasilkan. Tulis **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
```

## Keterangan


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