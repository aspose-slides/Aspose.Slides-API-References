---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. bool yazın.
type: docs
weight: 118
url: /tr/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) metot


Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. **bool** yazın.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// İlk slayt geçişini al
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// İleri slayt sonrası bayrağının işaretli olup olmadığını kontrol et
if (slideTransition->get_AdvanceAfter())
{
    // İleri slayt sonrası zaman değerini al
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Bakınız

* Sınıf [ISlideShowTransition](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)