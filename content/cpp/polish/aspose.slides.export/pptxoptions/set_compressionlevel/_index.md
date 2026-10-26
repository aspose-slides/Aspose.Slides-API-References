---
title: set_CompressionLevel()
second_title: Aspose.Slides dla C++ referencja API
description: "Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. Domyślna wartość to CompressionLevel::Level6."
type: docs
weight: 92
url: /pl/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metoda

Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. Domyślna wartość to [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
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