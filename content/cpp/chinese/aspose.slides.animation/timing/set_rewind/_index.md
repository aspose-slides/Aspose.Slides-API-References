---
title: set_Rewind()
second_title: Aspose.Slides for C++ API 参考
description: 此属性指定在播放完成后效果是否会倒回。写 bool.
type: docs
weight: 248
url: /zh/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) 方法


此属性指定在播放完成后效果是否会倒回。写 **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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

## 参见

* 类 [Timing](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)