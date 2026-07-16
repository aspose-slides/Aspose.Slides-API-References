---
title: set_IncludeOleData()
second_title: Référence API Aspose.Slides pour C++
description: True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Écrire bool.
type: docs
weight: 469
url: /fr/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) méthode

True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Écrire **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Remarques

La valeur par défaut est **false**. 

Exemple :
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