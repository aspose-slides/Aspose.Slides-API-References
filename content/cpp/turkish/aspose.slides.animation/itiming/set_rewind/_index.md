---
title: set_Rewind()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, etkinin çalma tamamlandığında geri sarıp sarmayacağını belirler. bool yazın.
type: docs
weight: 326
url: /tr/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) yöntemi

Bu öznitelik, efektin çalma tamamlandığında geri sarıp sarmayacağını belirler. **bool** yazın.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

## Diğer Bağlantılar

* Sınıf [ITiming](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)