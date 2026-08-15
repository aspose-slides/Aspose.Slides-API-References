---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性指定效果是否會持續重複至下一次點擊。讀取 bool.
type: docs
weight: 157
url: /zh-hant/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() 方法


此屬性指定效果是否會持續重複至下一次點擊。讀取 **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
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
* 函式庫 [Aspose.Slides](../../../)