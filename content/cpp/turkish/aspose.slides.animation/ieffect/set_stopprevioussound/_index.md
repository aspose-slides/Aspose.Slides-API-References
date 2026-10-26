---
title: set_StopPreviousSound()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmayacağını belirtir. bool yazın.
type: docs
weight: 209
url: /tr/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) metodu


Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmayacağını belirtir. **bool** yazın.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // İkinci efektin Enhancements/Sound ayarını "Stop Previous Sound" olarak değiştir
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## İlgili

* Sınıf [IEffect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)