---
title: set_AdvanceAfter()
second_title: Aspose.Slides için C++ API Referansı
description: Bu özellik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. bool yazın.
type: docs
weight: 118
url: /tr/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) metodu

Bu özellik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. **bool** yazın.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// İlk slayt geçişini al
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Advance Slide After bayrağının seçili olup olmadığını kontrol et
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After zaman değerini al
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Ayrıca Bakınız

* Sınıf [SlideShowTransition](../)
* İsim Alanı [Aspose::Slides::SlideShow](../../)
* Kütüphane [Aspose.Slides](../../../)