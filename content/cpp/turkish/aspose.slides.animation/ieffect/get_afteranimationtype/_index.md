---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API Referansı
description: Efekt için bir sonrası animasyon türü tanımlanmıştır. AfterAnimationType öğesini okuyun.
type: docs
weight: 222
url: /tr/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() yöntemi

Efekt için bir sonrası animasyon türü tanımlanmıştır. [AfterAnimationType](../../afteranimationtype/) okuyun.

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaytın ilk efektini al.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Efektin After animation değerini "Hide on Next Mouse Click" olarak değiştir
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Ayrıca Bakınız

* Enum [AfterAnimationType](../../afteranimationtype/)
* Sınıf [IEffect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)