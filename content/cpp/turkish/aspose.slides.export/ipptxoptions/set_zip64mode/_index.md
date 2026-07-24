---
title: set_Zip64Mode()
second_title: Aspose.Slides için C++ API Referansı
description: "Presentation belgesi için ZIP64 formatının kullanılıp kullanılmadığını belirtir. Varsayılan değer Zip64Mode::IfNecessary'dir."
type: docs
weight: 40
url: /tr/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metot


ZIP64 biçiminin [Presentation](../../../aspose.slides/presentation/) belgesi için kullanılıp kullanılmadığını belirtir. Varsayılan değer [Zip64Mode::IfNecessary](../../zip64mode/)'dir.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## Diğer Bilgiler

* Enum [Zip64Mode](../../zip64mode/)
* Sınıf [IPptxOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)