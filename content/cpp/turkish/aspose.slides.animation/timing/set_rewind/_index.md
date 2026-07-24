---
title: set_Rewind()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öznitelik, efektin çalma tamamlandığında geriye sarıp sarmayacağını belirtir. bool yazın.
type: docs
weight: 248
url: /tr/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) yöntemi

Bu öznitelik, efektin çalma tamamlandığında geriye sarıp sarmayacağını belirtir. **bool** yazın.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Açıklamalar

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slayt için efekt dizisini al.
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Ana dizinin ilk efektini al.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Efektin Timing/Rewind özelliğini etkinleştir.
effect->get_Timing()->set_Rewind(true);
```

## Bakınız

* Sınıf [Timing](../)
* AdAlanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)