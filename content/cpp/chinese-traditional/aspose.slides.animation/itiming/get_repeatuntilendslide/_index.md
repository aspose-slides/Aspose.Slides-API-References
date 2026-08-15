---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API 參考文件
description: 此屬性指定效果是否會持續重複至投影片結束。讀取 bool。
type: docs
weight: 131
url: /zh-hant/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() 方法

此屬性指定效果是否會持續重複至投影片結束。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 另請參閱

* 類別 [ITiming](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)