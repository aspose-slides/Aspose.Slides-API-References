---
title: set_StopPreviousSound()
second_title: Aspose.Slides C++ API Referansı
description: Bu öznitelik, animasyon etkisinin önceki sesi durdurup durdurmayacağını belirtir. bool yazın.
type: docs
weight: 209
url: /tr/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) metodu


Bu öznitelik, animasyon etkisinin önceki sesi durdurup durdurmayacağını belirtir. **bool** yazın.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaydın ilk efektini al.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// İkinci slaydın ilk efektini al.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // İkinci efektin Geliştirmeler/Ses özelliğini "Stop Previous Sound" olarak değiştir
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Diğer Bağlantılar

* Sınıf [Effect](../)
* Ad Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)