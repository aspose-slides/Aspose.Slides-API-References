---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. bool yazın.
type: docs
weight: 144
url: /tr/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) metod

Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. **bool** yazın.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// İlk slayt için efekt dizisini alır
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Ana dizinin ilk efektini alır.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Efektin Timing/Repeat değerini "Until End of Slide" olarak değiştirir
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Ayrıca Bakınız

* Sınıf [ITiming](../)
* İsim Uzayı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)