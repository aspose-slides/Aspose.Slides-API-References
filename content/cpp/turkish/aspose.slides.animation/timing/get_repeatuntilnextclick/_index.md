---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. bool okur.
type: docs
weight: 157
url: /tr/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() metodu


Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. **bool** okur.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Ayrıca Bakınız

* Sınıf [Timing](../)
* İsim Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)