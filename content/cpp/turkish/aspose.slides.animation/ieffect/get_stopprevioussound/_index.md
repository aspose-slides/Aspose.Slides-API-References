---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik animasyon etkisinin önceki sesi durdurup durdurmadığını belirtir. Okunur bool.
type: docs
weight: 196
url: /tr/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() metot


Bu öznitelik, animasyon etkisinin önceki sesi durdurup durdurmadığını belirtir. Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaytın ilk etkisini al.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// İkinci slaytın ilk etkisini al.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // İkinci efektin Enhancements/Sound özelliğini "Stop Previous Sound" olarak değiştir
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Ayrıca Bakınız

* Sınıf [IEffect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)