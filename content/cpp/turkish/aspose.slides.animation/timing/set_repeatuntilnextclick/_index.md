---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. bool yazın.
type: docs
weight: 170
url: /tr/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) metodu


Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. **bool** yazın.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
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
* İsim alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)