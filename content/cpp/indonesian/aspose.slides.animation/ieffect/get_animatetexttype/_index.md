---
title: get_AnimateTextType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan jenis animasi teks untuk efek. Teks bentuk dapat dianimasikan per huruf, per kata, atau sekaligus. Baca AnimateTextType.
type: docs
weight: 274
url: /id/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() metode


Mendefinisikan jenis animasi teks untuk efek. Teks bentuk dapat dianimasikan per huruf, per kata, atau sekaligus. Baca [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
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