---
title: set_AccessPermissions()
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsque le document est ouvert avec l'accès utilisateur. Voir PdfAccessPermissions.
type: docs
weight: 313
url: /fr/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) méthode


Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsque le document est ouvert avec l'accès utilisateur. Voir [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
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

* Énumération [PdfAccessPermissions](../../pdfaccesspermissions/)
* Classe [PdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)