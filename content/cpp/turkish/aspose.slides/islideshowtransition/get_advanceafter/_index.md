---
title: get_AdvanceAfter()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. Okunan bool.
type: docs
weight: 105
url: /tr/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() metodu

Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. Okunan **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// İlk slayt geçişini al
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Advance Slide After bayrağının işaretli olup olmadığını kontrol et
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After zaman değerini al
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Bakınız

* Sınıf [ISlideShowTransition](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)