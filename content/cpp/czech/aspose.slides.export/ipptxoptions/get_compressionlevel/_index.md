---
title: get_CompressionLevel()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Určuje úroveň komprese používanou při ukládání dokumentu prezentace. Výchozí hodnota je CompressionLevel::Level6."
type: docs
weight: 79
url: /cs/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() metoda


Specifikuje úroveň komprese používanou při ukládání dokumentu prezentace. Výchozí hodnota je [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Poznámky


Vyšší úrovně komprese vytvářejí menší soubory, ale vyžadují více času na zpracování. Skutečný kompresní poměr závisí na obsahu prezentace. 

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Viz také

* Enum [CompressionLevel](../../compressionlevel/)
* Třída [IPptxOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)