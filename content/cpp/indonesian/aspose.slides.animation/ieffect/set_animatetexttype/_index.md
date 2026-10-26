---
title: set_AnimateTextType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan jenis teks animasi untuk efek. Teks shape dapat dianimasikan per huruf, per kata, atau sekaligus. Tulis AnimateTextType.
type: docs
weight: 287
url: /id/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metode

Mendefinisikan jenis teks animasi untuk efek. Teks shape dapat dianimasikan per huruf, per kata, atau sekaligus. Tulis [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Catatan


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan efek pertama dari slide pertama.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ubah tipe animasi teks efek menjadi "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Lihat Juga

* Enum [AnimateTextType](../../animatetexttype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)