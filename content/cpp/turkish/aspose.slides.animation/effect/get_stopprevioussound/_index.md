---
title: get_StopPreviousSound()
second_title: C++ için Aspose.Slides API Referansı
description: Bu öznitelik, animasyon etkisinin önceki sesi durdurup durdurmadığını belirtir. Okur bool.
type: docs
weight: 196
url: /tr/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() metodu


Bu özellik, animasyon etkisinin önceki sesi durdurup durdurmadığını belirtir. Okur **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaytın ilk efektini al.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// İkinci slaytın ilk efektini al.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // İkinci efektin Enhancements/Sound'u "Stop Previous Sound" olarak değiştir
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Ayrıca Bakınız

* Sınıf [Effect](../)
* İsim Uzayı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)