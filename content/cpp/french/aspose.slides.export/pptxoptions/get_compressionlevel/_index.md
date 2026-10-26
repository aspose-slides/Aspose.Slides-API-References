---
title: get_CompressionLevel()
second_title: Référence API Aspose.Slides pour C++
description: "Spécifie le niveau de compression utilisé lors de l'enregistrement du document de présentation. La valeur par défaut est CompressionLevel::Level6."
type: docs
weight: 79
url: /fr/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() méthode


Spécifie le niveau de compression utilisé lors de l'enregistrement du document de présentation. La valeur par défaut est [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Remarques


Des niveaux de compression plus élevés produisent des fichiers plus petits mais nécessitent plus de temps de traitement. Le taux de compression réel dépend du contenu de la présentation. 

Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Voir aussi

* Enum [CompressionLevel](../../compressionlevel/)
* Classe [PptxOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)