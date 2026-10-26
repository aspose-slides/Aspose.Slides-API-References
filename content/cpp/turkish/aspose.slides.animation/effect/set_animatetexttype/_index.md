---
title: set_AnimateTextType()
second_title: Aspose.Slides for C++ API Referansı
description: Effect için bir animasyon metni türü tanımlar. Şekil metni harfe göre, kelimeye göre veya tümü birden animasyon yapılabilir. AnimateTextType yazın.
type: docs
weight: 287
url: /tr/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metodu

Effect için bir animasyon metni türü tanımlar. Şekil metni harfe göre, kelimeye göre veya tümü birden animasyon yapılabilir. [AnimateTextType](../../animatetexttype/) yazın.

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Diğer Bağlantılar

* Enum [AnimateTextType](../../animatetexttype/)
* Sınıf [Effect](../)
* AdAlanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)