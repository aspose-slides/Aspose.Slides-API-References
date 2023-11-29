---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API Reference
description: Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read AnimateTextType.
type: docs
weight: 274
url: /aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() method


Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
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
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)