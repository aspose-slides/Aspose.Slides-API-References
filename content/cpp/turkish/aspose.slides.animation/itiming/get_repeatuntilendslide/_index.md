---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öznitelik, efektin slaytın sonuna kadar tekrar edip etmeyeceğini belirtir. bool okunur.
type: docs
weight: 131
url: /tr/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() yöntemi


Bu öznitelik, efektin slaytın sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Diğer Bağlantılar

* Sınıf [ITiming](../)
* Ad Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)