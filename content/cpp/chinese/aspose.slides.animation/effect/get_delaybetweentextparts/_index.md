---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API 参考
description: 定义动画文本部件（单词或字母）之间的延迟。正值指定效果持续时间的百分比。负值指定以秒为单位的延迟。读取 float.
type: docs
weight: 300
url: /zh/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() 方法

定义动画文本部件（单词或字母）之间的延迟。正值指定效果持续时间的百分比。负值指定以秒为单位的延迟。读取 **float**。

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## 备注

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 获取第一张幻灯片的第一个效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 将效果 Animate text type 更改为 "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// 将动画文本部件之间的延迟设置为效果持续时间的 20%。
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## 另见

* 类 [Effect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)