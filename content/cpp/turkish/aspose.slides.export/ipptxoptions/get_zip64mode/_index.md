---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API Referansı
description: "ZIP64 formatının Presentation belgesi için kullanılıp kullanılmayacağını belirtir. Varsayılan değer Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /tr/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() metod


ZIP64 formatının [Presentation](../../../aspose.slides/presentation/) belgesi için kullanılıp kullanılmayacağını belirtir. Varsayılan değer [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## Diğer Bağlantılar

* Enum [Zip64Mode](../../zip64mode/)
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)