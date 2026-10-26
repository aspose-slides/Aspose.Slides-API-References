---
title: get_CompressionLevel()
second_title: Aspose.Slides för C++ API-referens
description: "Anger komprimeringsnivån som används när presentationsdokumentet sparas. Standardvärdet är CompressionLevel::Level6."
type: docs
weight: 79
url: /sv/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() metod


Anger komprimeringsnivån som används när presentationsdokumentet sparas. Standardvärdet är [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Anmärkningar


Högre komprimeringsnivåer ger mindre filer men kräver mer bearbetningstid. Det faktiska komprimeringsförhållandet beror på innehållet i presentationen. 

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Se även

* Enum [CompressionLevel](../../compressionlevel/)
* Klass [IPptxOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)