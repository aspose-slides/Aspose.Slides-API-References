---
title: get_Rewind()
second_title: Aspose.Slides C++ API Referansı
description: Bu öznitelik, etkinin çalma işlemi tamamlandığında geri sarılıp sarılmayacağını belirtir. Okunur bool.
type: docs
weight: 313
url: /tr/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() metod

Bu öznitelik, efektin oynatılması tamamlandığında geri sarılıp sarılmayacağını belirtir. Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Açıklamalar

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Ayrıca Bakınız

* Sınıf [ITiming](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)