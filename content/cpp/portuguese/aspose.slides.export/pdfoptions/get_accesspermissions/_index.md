---
title: get_AccessPermissions()
second_title: Aspose.Slides para C++ Referência da API
description: Contém um conjunto de indicadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja PdfAccessPermissions.
type: docs
weight: 300
url: /pt/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() método


Contém um conjunto de indicadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## Observações



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Veja Também

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Classe [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)