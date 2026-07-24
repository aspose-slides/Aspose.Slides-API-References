---
title: set_AnimateTextType()
second_title: Aspose.Slides C++ API Referansı
description: Efekt için bir metin animasyonu türü tanımlar. Şekil metni harf bazında, kelime bazında veya tümü bir kerede animasyon yapılabilir. AnimateTextType yazın.
type: docs
weight: 287
url: /tr/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) yöntemi

Efekt için bir metin animasyonu türü tanımlar. Şekil metni harf bazında, kelime bazında veya tümü bir kerede animasyon yapılabilir. Yazın [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slaydın ilk etkisini al.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Etkinin animasyon metin tipini "By letter" olarak değiştir
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Diğerlerine Bakın

* Enum [AnimateTextType](../../animatetexttype/)
* Sınıf [IEffect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)