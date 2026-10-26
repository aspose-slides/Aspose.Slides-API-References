---
title: get_Rewind()
second_title: Aspose.Slides C++ API 参考
description: 此属性指定效果在播放完成后是否会倒回。读取 bool.
type: docs
weight: 235
url: /zh/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() 方法


此属性指定效果在播放完成后是否会倒回。读取 **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## 另请参见

* 类 [Timing](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)