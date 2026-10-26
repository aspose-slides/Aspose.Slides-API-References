---
title: set_CompressionLevel()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is CompressionLevel::Level6."
type: docs
weight: 92
url: /nl/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) methode

Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Opmerkingen

Hogere compressieniveaus produceren kleinere bestanden, maar vereisen meer verwerkingstijd. De feitelijke compressieverhouding hangt af van de inhoud van de presentatie. 

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zie ook

* Enum [CompressionLevel](../../compressionlevel/)
* Klasse [IPptxOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)