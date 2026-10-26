---
title: get_CompressionLevel()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje úroveň komprese používanou při ukládání dokumentu prezentace. Výchozí hodnota je CompressionLevel::Level6."
type: docs
weight: 79
url: /cs/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() metoda

Určuje úroveň komprese používanou při ukládání dokumentu prezentace. Výchozí hodnota je [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Poznámky

Vyšší úrovně komprese produkují menší soubory, ale vyžadují více času na zpracování. Skutečný kompresní poměr závisí na obsahu prezentace. 

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Viz také

* Enum [CompressionLevel](../../compressionlevel/)
* Třída [PptxOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)