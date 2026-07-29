---
title: set_CompressionLevel()
second_title: Aspose.Slides för C++ API-referens
description: "Anger komprimeringsnivån som används när presentationsdokumentet sparas. Standardvärdet är CompressionLevel::Level6."
type: docs
weight: 92
url: /sv/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metod


Anger compressionnivån som används när presentationsdokumentet sparas. Standardvärdet är [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Anmärkningar


Högre komprimeringsnivåer ger mindre filer men kräver mer bearbetningstid. Den faktiska komprimeringsgraden beror på presentationens innehåll. 

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Se även

* Enum [CompressionLevel](../../compressionlevel/)
* Klass [PptxOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)