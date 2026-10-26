---
title: get_Zip64Mode()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentation document. De standaardwaarde is Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /nl/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() methode


Geeft aan of het ZIP64-formaat wordt gebruikt voor het [Presentation](../../../aspose.slides/presentation/) document. De standaardwaarde is [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
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
* Klasse [IPptxOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)