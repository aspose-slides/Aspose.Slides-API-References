---
title: set_Zip64Mode()
second_title: Aspose.Slides için C++ API Referansı
description: "Sunum belgesi için ZIP64 formatının kullanılıp kullanılmadığını belirtir. Varsayılan değer Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /tr/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) method

ZIP64 formatının [Presentation](../../../aspose.slides/presentation/) belgesi için kullanılıp kullanılmadığını belirtir. Varsayılan değer [Zip64Mode::IfNecessary](../../zip64mode/)'dir.

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## İlgili

* Enum [Zip64Mode](../../zip64mode/)
* Sınıf [PptxOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)