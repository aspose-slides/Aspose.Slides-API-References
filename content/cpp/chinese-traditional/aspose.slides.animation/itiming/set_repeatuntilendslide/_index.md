---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides C++ API 參考
description: 此屬性指定效果是否會重複至投影片結束。寫入 bool。
type: docs
weight: 144
url: /zh-hant/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) 方法


此屬性指定若效果會重複直到投影片結束。寫入 **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// 取得第一張投影片的效果序列
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// 取得主要序列的第一個效果。
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 將效果的 Timing/Repeat 更改為「直到投影片結束」
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 另見

* 類別 [ITiming](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)