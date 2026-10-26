---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides için C++ API Referansı
description: Animasyonlu metin parçaları (kelimeler veya harfler) arasında bir gecikme tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer, saniye cinsinden gecikmeyi belirtir. float olarak okunur.
type: docs
weight: 300
url: /tr/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() yöntemi


Animasyonlu metin parçaları (kelimeler veya harfler) arasında gecikme tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer, saniye cinsinden gecikmeyi belirtir. **float** tipinde okunur.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
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

## Ayrıca Bakınız

* Sınıf [Effect](../)
* İsim Uzayı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)