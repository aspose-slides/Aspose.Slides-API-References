---
title: set_IncludeOleData()
second_title: Référence de l'API Aspose.Slides pour C++
description: true pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant. Écrire bool.
type: docs
weight: 469
url: /fr/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) méthode

true pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant. Écrire **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

* Classe [IPdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)