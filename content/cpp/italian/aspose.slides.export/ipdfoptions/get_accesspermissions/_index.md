---
title: get_AccessPermissions()
second_title: Aspose.Slides per C++ Riferimento API
description: Contiene un insieme di flag che specificano quali autorizzazioni di accesso devono essere concesse quando il documento viene aperto con l'accesso utente. Vedi PdfAccessPermissions.
type: docs
weight: 261
url: /it/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() metodo

Contiene un insieme di flag che specificano quali autorizzazioni di accesso devono essere concesse quando il documento viene aperto con l'accesso utente. Vedi [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
```

## Osservazioni



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Vedi anche

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Classe [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)