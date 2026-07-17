---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides C++ API 参考
description: 定义动画文本部件（单词或字母）之间的延迟。正值指定效果持续时间的百分比。负值指定以秒为单位的延迟。写入 float.
type: docs
weight: 313
url: /zh/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) 方法


定义动画文本部件（单词或字母）之间的延迟。正值指定效果持续时间的百分比。负值指定以秒为单位的延迟。写入 **float**。

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
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

## 另见

* 类 [Effect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)