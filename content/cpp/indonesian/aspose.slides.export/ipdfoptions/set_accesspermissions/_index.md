---
title: set_AccessPermissions()
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi satu set flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat PdfAccessPermissions.
type: docs
weight: 274
url: /id/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) metode

Berisi satu set flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* Kelas [IPdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)