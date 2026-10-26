---
title: set_AnimateTextType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan jenis animasi teks untuk efek. Teks bentuk dapat dianimasikan per huruf, per kata, atau sekaligus. Tulis AnimateTextType.
type: docs
weight: 287
url: /id/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metode

Mendefinisikan jenis animasi teks untuk efek. Teks bentuk dapat dianimasikan per huruf, per kata, atau sekaligus. Tulis [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
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
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)