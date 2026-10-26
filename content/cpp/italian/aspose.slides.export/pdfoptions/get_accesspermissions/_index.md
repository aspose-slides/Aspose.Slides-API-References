---
title: get_AccessPermissions()
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento viene aperto con l'accesso dell'utente. Vedi PdfAccessPermissions.
type: docs
weight: 300
url: /it/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() metodo

Contiene un insieme di flag che specificano quali permessi di accesso dovrebbero essere concessi quando il documento viene aperto con l'accesso dell'utente. Vedi [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## Note

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Vedi anche

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Classe [PdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)