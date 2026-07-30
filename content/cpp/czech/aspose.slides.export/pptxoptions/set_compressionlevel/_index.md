---
title: set_CompressionLevel()
second_title: Aspose.Slides pro referenci API C++
description: "Určuje úroveň komprese používanou při ukládání souboru prezentace. Výchozí hodnota je CompressionLevel::Level6."
type: docs
weight: 92
url: /cs/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metoda


Určuje úroveň komprese používanou při ukládání souboru prezentace. Výchozí hodnota je [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Poznámky


Vyšší úrovně komprese vytvářejí menší soubory, ale vyžadují více času na zpracování. Skutečný poměr komprese závisí na obsahu prezentace. 

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Viz také

* Výčet [CompressionLevel](../../compressionlevel/)
* Třída [PptxOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)