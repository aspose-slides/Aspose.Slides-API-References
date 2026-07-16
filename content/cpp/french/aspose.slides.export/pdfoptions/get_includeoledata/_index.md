---
title: get_IncludeOleData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lire bool.
type: docs
weight: 456
url: /fr/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() méthode

Vrai pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant. Lire **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Remarques

La valeur par défaut est **false**. 

Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Voir aussi

* Classe [PdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)