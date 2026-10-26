---
title: get_DetectTables()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan apakah mendeteksi tabel saat mengimpor file pdf.
type: docs
weight: 1
url: /id/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const metode

Menentukan apakah mendeteksi tabel saat mengimpor file pdf.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Catatan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [PdfImportOptions](../)
* Ruang Nama [Aspose::Slides::Import](../../)
* Perpustakaan [Aspose.Slides](../../../)