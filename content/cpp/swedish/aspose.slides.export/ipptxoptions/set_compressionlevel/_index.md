---
title: set_CompressionLevel()
second_title: Aspose.Slides för C++ API-referens
description: "Anger komprimeringsnivån som används när presentationsdokumentet sparas. Standardvärdet är CompressionLevel::Level6."
type: docs
weight: 92
url: /sv/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metod

Anger komprimeringsnivån som används när presentationsdokumentet sparas. Standardvärdet är [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Anmärkningar

Högre komprimeringsnivåer ger mindre filer men kräver mer behandlingstid. Den faktiska komprimeringsgraden beror på innehållet i presentationen. 

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Se också

* Enum [CompressionLevel](../../compressionlevel/)
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)