---
title: get_AnimateTextType()
second_title: Aspose.Slides için C++ API Referansı
description: Efekt için bir animasyon metin türü tanımlar. Şekil metni harfe, kelimeye göre veya hepsi birden animasyonlu hale getirilebilir. Okuyun AnimateTextType.
type: docs
weight: 274
url: /tr/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() yöntem


Efekt için bir animasyon metin türü tanımlar. Şekil metni harfe, kelimeye göre veya hepsi birden animasyonlu hale getirilebilir. Oku [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## İlgili

* Enum [AnimateTextType](../../animatetexttype/)
* Sınıf [Effect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)