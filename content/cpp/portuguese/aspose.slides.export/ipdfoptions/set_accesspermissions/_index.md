---
title: set_AccessPermissions()
second_title: Referência da API Aspose.Slides para C++
description: Contém um conjunto de bandeiras que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Consulte PdfAccessPermissions.
type: docs
weight: 274
url: /pt/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) método


Contém um conjunto de bandeiras que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## Observações



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Ver também

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Classe [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)