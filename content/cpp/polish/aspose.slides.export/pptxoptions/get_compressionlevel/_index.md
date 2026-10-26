---
title: get_CompressionLevel()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. Domyślna wartość to CompressionLevel::Level6."
type: docs
weight: 79
url: /pl/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() metoda


Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. Domyślna wartość to [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Uwagi


Wyższe poziomy kompresji powodują mniejsze pliki, ale wymagają więcej czasu przetwarzania. Rzeczywisty współczynnik kompresji zależy od treści prezentacji. 

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zobacz także

* Enum [CompressionLevel](../../compressionlevel/)
* Klasa [PptxOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)