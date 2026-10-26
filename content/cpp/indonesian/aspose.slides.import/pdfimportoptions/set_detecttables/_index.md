---
title: set_DetectTables()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah mendeteksi tabel saat mengimpor file PDF.
type: docs
weight: 14
url: /id/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) metode


Menentukan apakah mendeteksi tabel saat mengimpor file PDF.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
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