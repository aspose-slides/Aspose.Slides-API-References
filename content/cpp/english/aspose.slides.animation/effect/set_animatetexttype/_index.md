---
title: set_AnimateTextType()
second_title: Aspose.Slides for C++ API Reference
description: Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Write AnimateTextType.
type: docs
weight: 287
url: /aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) method


Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Write [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## See Also

* Enum [AnimateTextType](../../animatetexttype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)