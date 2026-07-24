---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, efektin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. Write bool.
type: docs
weight: 170
url: /tr/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) yöntemi


Bu öznitelik, efektin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. Yazın **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// İlk slayt için efekt dizisini alır
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Ana dizinin ilk etkisini alır.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Etkinin Zamanlama/Repeat'ini "Slayt Sonuna Kadar" olarak değiştirir
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## İlgili

* Sınıf [ITiming](../)
* İsim Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)