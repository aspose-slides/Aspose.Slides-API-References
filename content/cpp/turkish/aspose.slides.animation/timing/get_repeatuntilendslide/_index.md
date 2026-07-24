---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur bool.
type: docs
weight: 131
url: /tr/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() metod


Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
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

## Ayrıca Bakınız

* Sınıf [Timing](../)
* Ad Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)