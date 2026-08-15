---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性指定效果是否會持續重複至下一次點擊。寫入 bool。
type: docs
weight: 170
url: /zh-hant/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) 方法


此屬性指定效果是否會持續重複至下一次點擊。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// 取得第一張投影片的效果序列
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// 取得主要序列的第一個效果。
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 將效果的 Timing/Repeat 更改為「直到投影片結束」
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## 另請參閱

* 類別 [ITiming](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 程式庫 [Aspose.Slides](../../../)