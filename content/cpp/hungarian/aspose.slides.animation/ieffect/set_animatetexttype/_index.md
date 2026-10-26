---
title: set_AnimateTextType()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a hatás animált szöveg típusát. A forma szövege animálható betűnként, szónként vagy egyszerre. Írja be az AnimateTextType.
type: docs
weight: 287
url: /hu/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metódus


Meghatározza a hatás animált szöveg típusát. A forma szövege animálható betűnként, szónként vagy egyszerre. Írja be a [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
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
* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)