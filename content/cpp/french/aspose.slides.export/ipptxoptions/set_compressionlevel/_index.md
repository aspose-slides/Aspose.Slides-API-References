---
title: set_CompressionLevel()
second_title: Référence API Aspose.Slides pour C++
description: "Spécifie le niveau de compression utilisé lors de l'enregistrement du document de présentation. La valeur par défaut est CompressionLevel::Level6."
type: docs
weight: 92
url: /fr/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) méthode

Spécifie le niveau de compression utilisé lors de l’enregistrement du document de présentation. La valeur par défaut est [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Remarques

Des niveaux de compression plus élevés produisent des fichiers plus petits mais nécessitent plus de temps de traitement. Le taux de compression réel dépend du contenu de la présentation. 

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Voir aussi

* Enum [CompressionLevel](../../compressionlevel/)
* Classe [IPptxOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)