---
title: set_Zip64Mode()
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Spécifie si le format ZIP64 est utilisé pour le document Presentation. La valeur par défaut est Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /fr/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) méthode

Spécifie si le format ZIP64 est utilisé pour le document [Presentation](../../../aspose.slides/presentation/). La valeur par défaut est [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
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
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)