---
title: get_AdvanceAfter()
second_title: Aspose.Slides için C++ API Referansı
description: Bu özellik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. bool olarak okunur.
type: docs
weight: 105
url: /tr/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() metot

Bu özellik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. **bool** okunur.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// İlk slayt geçişini al
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// İleri Kaydırma Sonrası bayrağının işaretli olup olmadığını kontrol et
if (slideTransition->get_AdvanceAfter())
{
    // İleri Kaydırma Sonrası Süre değerini al
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Ayrıca Bakınız

* Sınıf [SlideShowTransition](../)
* Ad Alanı [Aspose::Slides::SlideShow](../../)
* Kütüphane [Aspose.Slides](../../../)