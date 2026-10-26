---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides C++ API 参考
description: 定义动画文本片段（单词或字母）之间的延迟。正值表示效果持续时间的百分比。负值表示以秒为单位的延迟。写入 float.
type: docs
weight: 313
url: /zh/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) method


定义在动画文本片段（单词或字母）之间的延迟。正值表示效果持续时间的百分比。负值表示以秒为单位的延迟。写入 **float**。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## 另请参见

* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)