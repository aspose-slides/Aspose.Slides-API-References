---
title: set_AccessPermissions()
second_title: Référence API Aspose.Slides pour C++
description: Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec l'accès utilisateur. Voir PdfAccessPermissions.
type: docs
weight: 274
url: /fr/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) méthode

Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec l'accès utilisateur. Voir [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)