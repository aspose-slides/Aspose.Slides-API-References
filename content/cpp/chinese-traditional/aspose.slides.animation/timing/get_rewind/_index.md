---
title: get_Rewind()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性指定效果在播放完成後是否會倒帶。讀取 bool.
type: docs
weight: 235
url: /zh-hant/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() 方法


此屬性指定效果在播放完成後是否會倒帶。讀取 **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## 另見

* 類別 [Timing](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)