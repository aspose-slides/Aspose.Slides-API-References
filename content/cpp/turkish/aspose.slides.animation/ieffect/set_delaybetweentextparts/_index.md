---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API Referansı
description: Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, etkinin süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye cinsinden belirtir. float yazın.
type: docs
weight: 313
url: /tr/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) yöntemi


Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, etkinin süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye cinsinden belirtir. **float** olarak yazın.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slayttaki ilk efekti al.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Efektin AnimateText türünü "By word" olarak değiştir.
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Animasyonlu metin parçaları arasındaki gecikmeyi efekt süresinin %20'si olarak ayarla.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Diğer Bağlantılar

* Sınıf [IEffect](../)
* AdAlanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)