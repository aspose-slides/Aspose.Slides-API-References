---
title: get_Rewind()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öznitelik, efektin çalması bittiğinde geri sarılıp sarılmayacağını belirtir. Okunur bool.
type: docs
weight: 235
url: /tr/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() metodu


Bu öznitelik, efektin çalması bittiğinde geri sarılıp sarılmayacağını belirtir. Okunur **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slayt için efekt dizisini al.
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Ana dizinin ilk efektini al.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Efekt Timing/Rewind özelliğini etkinleştir.
effect->get_Timing()->set_Rewind(true);
```

## İlgili

* Sınıf [Timing](../)
* Ad Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)