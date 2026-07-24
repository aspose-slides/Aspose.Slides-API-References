---
title: Compress
second_title: Aspose.Slides için C++ API Referansı
description: Presentation'ı sıkıştırmak amaçlı bir grup yöntemi temsil eder.
type: docs
weight: 14
url: /tr/aspose.slides.lowcode/compress/
---
## Compress sınıfı

[Presentation](../../aspose.slides/presentation/)'ı sıkıştırmak için tasarlanmış bir grup yöntemi temsil eder.

```cpp
class Compress
```

## Methods

| Yöntem | Açıklama |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Embedded fontlardan kullanılmayan karakterleri kaldırarak [Presentation](../../aspose.slides/presentation/)'ın sıkıştırılmasını sağlar. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Kullanılmayan yerleşim slaytlarını kaldırarak [Presentation](../../aspose.slides/presentation/)'ın sıkıştırılmasını sağlar. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Kullanılmayan ana slaytları kaldırarak [Presentation](../../aspose.slides/presentation/)'in sıkıştırılmasını sağlar. |

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Adalanı [Aspose::Slides::LowCode](../)
* Kütüphane [Aspose.Slides](../../)