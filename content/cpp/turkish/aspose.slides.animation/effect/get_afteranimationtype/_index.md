---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API Referansı
description: Effect için bir sonraki animasyon türünü tanımlar. AfterAnimationType'ı okuyun.
type: docs
weight: 222
url: /tr/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() metodu


Effect için bir sonraki animasyon türünü tanımlar. [AfterAnimationType](../../afteranimationtype/)'yi okuyun.

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Ayrıca Bakınız

* Enum [AfterAnimationType](../../afteranimationtype/)
* Sınıf [Effect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)