---
title: set_Zip64Mode()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentation-document. De standaardwaarde is Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /nl/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) methode

Specificeert of het ZIP64-formaat wordt gebruikt voor het [Presentation](../../../aspose.slides/presentation/) document. De standaardwaarde is [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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

* Enum [Zip64Mode](../../zip64mode/)
* Klasse [PptxOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)