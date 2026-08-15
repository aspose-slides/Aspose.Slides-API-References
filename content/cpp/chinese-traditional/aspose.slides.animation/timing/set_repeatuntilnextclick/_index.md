---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性指定效果是否會持續重複，直到下一次點擊。寫入 bool.
type: docs
weight: 170
url: /zh-hant/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) 方法


此屬性指定效果是否會持續重複，直到下一次點擊。寫入 **bool**。

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## 另請參閱

* 類別 [Timing](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 程式庫 [Aspose.Slides](../../../)