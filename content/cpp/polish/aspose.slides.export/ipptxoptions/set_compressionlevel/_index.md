---
title: set_CompressionLevel()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. Domyślna wartość to CompressionLevel::Level6."
type: docs
weight: 92
url: /pl/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metoda

Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. Domyślna wartość to [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Uwagi

Wyższe poziomy kompresji tworzą mniejsze pliki, ale wymagają więcej czasu przetwarzania. Rzeczywisty współczynnik kompresji zależy od zawartości prezentacji. 

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zobacz także

* Wyliczenie [CompressionLevel](../../compressionlevel/)
* Klasa [IPptxOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)