---
title: set_Rewind()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性指定效果在播放完成後是否會倒帶。寫入 bool.
type: docs
weight: 248
url: /zh-hant/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) 方法


此屬性指定效果在播放完成後是否會倒帶。寫入 **bool**。

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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
* 程式庫 [Aspose.Slides](../../../)