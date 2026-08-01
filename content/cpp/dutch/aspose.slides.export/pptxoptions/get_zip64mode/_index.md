---
title: get_Zip64Mode()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. De standaardwaarde is Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /nl/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() methode


Specificeert of het ZIP64-formaat wordt gebruikt voor het [Presentation](../../../aspose.slides/presentation/) document. De standaardwaarde is [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zie ook

* Enumeratie [Zip64Mode](../../zip64mode/)
* Klasse [PptxOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)