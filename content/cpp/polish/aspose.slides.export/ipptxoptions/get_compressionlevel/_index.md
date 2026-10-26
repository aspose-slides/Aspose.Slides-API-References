---
title: get_CompressionLevel()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. Domyślna wartość to CompressionLevel::Level6."
type: docs
weight: 79
url: /pl/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() metoda

Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. Domyślna wartość to [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
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

* Enum [CompressionLevel](../../compressionlevel/)
* Klasa [IPptxOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)