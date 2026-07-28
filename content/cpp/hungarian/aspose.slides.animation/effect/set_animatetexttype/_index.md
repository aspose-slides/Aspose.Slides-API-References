---
title: set_AnimateTextType()
second_title: Aspose.Slides C++ API Referencia
description: Meghatározza az animált szöveg típusát a hatáshoz. Az alakzat szövege betűnként, szónként vagy egyszerre animálható. Írja be az AnimateTextType.
type: docs
weight: 287
url: /hu/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metódus


Meghatározza az animált szöveg típusát a hatáshoz. A alakzat szövege animálható betűnként, szó szerint vagy egyszerre. Írja [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
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
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)