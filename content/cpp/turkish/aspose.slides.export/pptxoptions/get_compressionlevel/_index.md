---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API Referansı
description: "Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer CompressionLevel::Level6'dır."
type: docs
weight: 79
url: /tr/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() metodu

Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Açıklamalar

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işlem süresi gerektirir. Gerçek sıkıştırma oranı, sunum içeriğine bağlıdır.

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ayrıca Bakınız

* Enum [CompressionLevel](../../compressionlevel/)
* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)