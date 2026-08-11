---
title: get_AnimateTextType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد نوع نص متحرك للتأثير. يمكن تحريك نص الشكل حرفًا، كلمةً أو بالكامل مرة واحدة. اقرأ AnimateTextType.
type: docs
weight: 274
url: /ar/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() طريقة

يحدد نوع نص متحرك للتأثير. يمكن تحريك نص الشكل حرفًا، كلمةً أو بالكامل مرة واحدة. اقرأ [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## انظر أيضًا

* تعداد [AnimateTextType](../../animatetexttype/)
* فئة [Effect](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)