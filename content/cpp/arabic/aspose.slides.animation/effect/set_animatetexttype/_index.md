---
title: set_AnimateTextType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد نوع نص متحرك للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو كله مرة واحدة. اكتب AnimateTextType.
type: docs
weight: 287
url: /ar/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) طريقة

يحدد نوع نص تحريكي للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو كله مرة واحدة. اكتب [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على التأثير الأول للشريحة الأولى.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// غيّر نوع النص المتحرك للتأثير إلى "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## انظر أيضًا

* تعداد [AnimateTextType](../../animatetexttype/)
* فئة [Effect](../)
* مساحة الأسماء [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)