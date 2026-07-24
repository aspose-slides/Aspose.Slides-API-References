---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API Referansı
description: Bu özellik, etkinin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. bool yazın.
type: docs
weight: 144
url: /tr/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) metodu


Bu özellik, efektin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. **bool** yazın.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
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

## Diğer bakınız

* Sınıf [Timing](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)