---
title: get_Zip64Mode()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie si le format ZIP64 est utilisé pour le document Presentation. La valeur par défaut est Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /fr/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() méthode


Spécifie si le format ZIP64 est utilisé pour le document [Presentation](../../../aspose.slides/presentation/). La valeur par défaut est [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Voir aussi

* Enum [Zip64Mode](../../zip64mode/)
* Classe [PptxOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)