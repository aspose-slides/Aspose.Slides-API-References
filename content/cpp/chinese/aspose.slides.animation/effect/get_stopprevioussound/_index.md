---
title: get_StopPreviousSound()
second_title: Aspose.Slides C++ API 参考
description: 此属性指定动画效果是否停止先前的声音。读取 bool。
type: docs
weight: 196
url: /zh/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() 方法

此属性指定动画效果是否停止先前的声音。读取 **bool**。

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
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

## 参见

* 类 [Effect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)