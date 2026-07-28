---
title: get_AnimateTextType()
second_title: Aspose.Slides C++ API referencia
description: Definiál egy animált szövegtípust a hatáshoz. A forma szövege betűnként, szóanként vagy egyszerre animálható. Olvassa el az AnimateTextType.
type: docs
weight: 274
url: /hu/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() metódus

Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Megjegyzések

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Lásd még

* Enum [AnimateTextType](../../animatetexttype/)
* osztály [Effect](../)
* névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)