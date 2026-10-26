---
title: get_AnimateTextType()
second_title: Aspose.Slides C++ için API Referansı
description: Bir efekt için hareketli metin türünü tanımlar. Şekil metni harf bazında, kelime bazında veya tümü bir anda animasyonlu hâle getirilebilir. AnimateTextType'ı okuyun.
type: docs
weight: 274
url: /tr/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() metodu


Bir efekt için hareketli metin türünü tanımlar. Şekil metni harf bazında, kelime bazında veya tamamı bir anda animasyonlu hale getirilebilir. Oku [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk slayttaki ilk efekti al.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Efektin AnimateTextType değerini "By letter" olarak değiştir
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Bakınız

* Enum [AnimateTextType](../../animatetexttype/)
* Sınıf [IEffect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)