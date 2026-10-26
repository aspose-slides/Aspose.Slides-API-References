---
title: get_AnimateTextType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan jenis animasi teks untuk efek. Teks bentuk dapat dianimasikan per huruf, per kata, atau sekaligus. Baca AnimateTextType.
type: docs
weight: 274
url: /id/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() metode

Mendefinisikan jenis animasi teks untuk efek. Teks bentuk dapat dianimasikan per huruf, per kata, atau sekaligus. Baca [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Catatan

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Lihat Juga

* Enum [AnimateTextType](../../animatetexttype/)
* Kelas [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)