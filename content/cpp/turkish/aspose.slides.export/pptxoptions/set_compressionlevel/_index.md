---
title: set_CompressionLevel()
second_title: Aspose.Slides for C++ API Referansı
description: "Sunum belgesini kaydederken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer CompressionLevel::Level6'dır."
type: docs
weight: 92
url: /tr/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metot

Sunum belgesini kaydederken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Açıklamalar

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işleme süresi gerektirir. Gerçek sıkıştırma oranı, sunumun içeriğine bağlıdır. 

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Diğer Bilgiler

* Enum [CompressionLevel](../../compressionlevel/)
* Sınıf [PptxOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)