---
title: set_AccessPermissions()
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi satu set flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat PdfAccessPermissions.
type: docs
weight: 313
url: /id/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) metode

Berisi satu set flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Catatan



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Lihat Juga

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Kelas [PdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)