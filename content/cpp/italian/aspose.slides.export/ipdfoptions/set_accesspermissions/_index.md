---
title: set_AccessPermissions()
second_title: Riferimento API Aspose.Slides per C++
description: Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento viene aperto con l'accesso dell'utente. Vedi PdfAccessPermissions.
type: docs
weight: 274
url: /it/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) metodo


Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento viene aperto con l'accesso dell'utente. Vedi [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)