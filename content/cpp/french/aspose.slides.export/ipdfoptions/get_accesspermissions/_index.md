---
title: get_AccessPermissions()
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec l'accès utilisateur. Voir PdfAccessPermissions.
type: docs
weight: 261
url: /fr/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() méthode


Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec l'accès utilisateur. Voir [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* Classe [IPdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)