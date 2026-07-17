---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ API 参考
description: 此属性指定动画效果是否停止先前的声音。读取 bool。
type: docs
weight: 196
url: /zh/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() 方法

此属性指定动画效果是否停止先前的声音。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## 备注

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 获取第一张幻灯片的第一个效果。
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// 获取第二张幻灯片的第一个效果。
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // 将第二个效果的增强/声音更改为“Stop Previous Sound”
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 另见

* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)