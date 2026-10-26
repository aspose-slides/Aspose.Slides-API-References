---
title: set_Zip64Mode()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Indique si le format ZIP64 est utilisé pour le document Presentation. La valeur par défaut est Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /fr/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) méthode

Indique si le format ZIP64 est utilisé pour le document [Presentation](../../../aspose.slides/presentation/). La valeur par défaut est [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Remarques

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Voir aussi

* Enum [Zip64Mode](../../zip64mode/)
* classe [PptxOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)