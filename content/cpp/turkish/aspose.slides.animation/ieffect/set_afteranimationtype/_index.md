---
title: set_AfterAnimationType()
second_title: Aspose.Slides C++ API Referansı
description: Efekt için bir AfterAnimationType türü tanımlanır. AfterAnimationType yazın.
type: docs
weight: 235
url: /tr/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metot


Efekt için AfterAnimationType türü tanımlanır. [AfterAnimationType](../../afteranimationtype/) yazın.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaydın ilk efektini al.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Efektin After animation türünü "Hide on Next Mouse Click" olarak değiştir
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Ayrıca bakınız

* Enum [AfterAnimationType](../../afteranimationtype/)
* Sınıf [IEffect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)