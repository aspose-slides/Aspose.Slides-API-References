---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API 参考
description: 为效果定义动画文本类型。形状文本可以按字母、按单词或一次性全部进行动画。阅读 AnimateTextType.
type: docs
weight: 274
url: /zh/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() 方法


为效果定义一个动画文本类型。形状文本可以按字母、按单词或一次性全部进行动画。阅读 [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 另见

* 枚举 [AnimateTextType](../../animatetexttype/)
* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)