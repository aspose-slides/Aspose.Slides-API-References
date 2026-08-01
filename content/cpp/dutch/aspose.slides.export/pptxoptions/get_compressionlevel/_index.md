---
title: get_CompressionLevel()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is CompressionLevel::Level6."
type: docs
weight: 79
url: /nl/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() methode

Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Opmerkingen

Hogere compressieniveaus produceren kleinere bestanden maar vereisen meer verwerkingstijd. De werkelijke compressieverhouding hangt af van de inhoud van de presentatie. 

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zie ook

* Enum [CompressionLevel](../../compressionlevel/)
* Klasse [PptxOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)