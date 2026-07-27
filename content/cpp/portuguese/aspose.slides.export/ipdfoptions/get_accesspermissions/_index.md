---
title: get_AccessPermissions()
second_title: Referência da API Aspose.Slides para C++
description: Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja PdfAccessPermissions.
type: docs
weight: 261
url: /pt/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() método


Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)