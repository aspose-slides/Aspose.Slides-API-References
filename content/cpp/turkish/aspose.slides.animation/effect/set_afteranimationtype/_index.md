---
title: set_AfterAnimationType()
second_title: Aspose.Slides for C++ API Referansı
description: Etki için bir sonrası animasyon türü tanımlar. AfterAnimationType yazın.
type: docs
weight: 235
url: /tr/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metod

Etki için bir sonrası animasyon türü tanımlar. [AfterAnimationType](../../afteranimationtype/)'yi yazın.

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaydın ilk efektini al.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Efektin After animation özelliğini "Hide on Next Mouse Click" olarak değiştir
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Diğer

* Enum [AfterAnimationType](../../afteranimationtype/)
* Sınıf [Effect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)