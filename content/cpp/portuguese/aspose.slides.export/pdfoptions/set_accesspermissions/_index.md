---
title: set_AccessPermissions()
second_title: Referência da API Aspose.Slides para C++
description: Contém um conjunto de bandeiras que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja PdfAccessPermissions.
type: docs
weight: 313
url: /pt/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) método

Contém um conjunto de bandeiras que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
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
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)