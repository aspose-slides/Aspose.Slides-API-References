---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API Referansı
description: Animasyonlu metin parçaları (kelimeler veya harfler) arasında gecikme tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye cinsinden belirtir. float okunur.
type: docs
weight: 300
url: /tr/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() yöntemi

Animasyonlu metin parçaları (kelimeler veya harfler) arasında gecikme tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye cinsinden belirtir. Okunur **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## İlgili Bağlantılar

* Sınıf [IEffect](../)
* İsim Uzayı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)