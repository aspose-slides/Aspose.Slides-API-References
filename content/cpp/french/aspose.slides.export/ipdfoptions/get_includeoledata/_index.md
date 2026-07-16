---
title: get_IncludeOleData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vrai pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant. Lecture bool.
type: docs
weight: 456
url: /fr/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() méthode

Vrai pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

* Classe [IPdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)