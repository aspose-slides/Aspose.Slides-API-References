---
title: get_AccessPermissions()
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna. Lihat PdfAccessPermissions.
type: docs
weight: 300
url: /id/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() metode

Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
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
* Library [Aspose.Slides](../../../)