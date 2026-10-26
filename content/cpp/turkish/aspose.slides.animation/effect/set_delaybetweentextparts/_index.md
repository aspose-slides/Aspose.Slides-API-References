---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides için C++ API Referansı
description: Animasyonlu metin parçaları (kelimeler veya harfler) arasında bir gecikme tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer, gecikmeyi saniye cinsinden belirtir. float yazın.
type: docs
weight: 313
url: /tr/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) yöntemi

Animasyonlu metin parçaları (kelimeler veya harfler) arasında bir gecikme tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer, gecikmeyi saniye cinsinden belirtir. **float** yazın.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaydın ilk efektini al.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Efektin AnimateTextType değerini "By word" olarak ayarla
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Etki süresinin %20'si kadar animasyonlu metin parçaları arasındaki gecikmeyi ayarla.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Ayrıca Bakınız

* Sınıf [Effect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)