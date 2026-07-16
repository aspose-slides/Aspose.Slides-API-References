---
title: get_AccessPermissions()
second_title: Référence API Aspose.Slides pour C++
description: Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir PdfAccessPermissions.
type: docs
weight: 300
url: /fr/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() méthode


Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## Remarques



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Voir aussi

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Classe [PdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)