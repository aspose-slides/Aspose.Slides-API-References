---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. bool okunur.
type: docs
weight: 157
url: /tr/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() metodu


Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. **bool** okunur.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// İlk slayt için efekt dizisini alır
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Ana dizinin ilk efektini alır.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Efektin Timing/Repeat özelliğini "Slayt Sonuna Kadar" olarak değiştirir
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Diğerlerine Bak

* Sınıf [ITiming](../)
* Ad Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)