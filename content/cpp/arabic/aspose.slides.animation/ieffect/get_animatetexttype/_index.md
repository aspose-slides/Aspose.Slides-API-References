---
title: get_AnimateTextType()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد نوع نص متحرك للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو كله مرة واحدة. اقرأ AnimateTextType.
type: docs
weight: 274
url: /ar/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() طريقة

يحدد نوع نص متحرك للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو كله مرة واحدة. اقرأ [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على التأثير الأول في الشريحة الأولى.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// غيّر نوع نص التحريك للتأثير إلى "حسب الحرف"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## انظر أيضًا

* عدد [AnimateTextType](../../animatetexttype/)
* فئة [IEffect](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)