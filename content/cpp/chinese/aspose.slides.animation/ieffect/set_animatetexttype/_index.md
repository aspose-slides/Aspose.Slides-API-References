---
title: set_AnimateTextType()
second_title: Aspose.Slides C++ API 参考
description: 定义效果的动画文本类型。形状文本可以按字母、按单词或一次性全部动画。写入 AnimateTextType.
type: docs
weight: 287
url: /zh/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) 方法


定义效果的动画文本类型。形状文本可以按字母、按单词或一次性全部动画。写入 [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 另请参阅

* 枚举 [AnimateTextType](../../animatetexttype/)
* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)