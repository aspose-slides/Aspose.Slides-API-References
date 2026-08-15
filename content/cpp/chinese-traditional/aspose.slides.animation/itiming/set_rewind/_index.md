---
title: set_Rewind()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性指定效果在播放完成後是否會倒帶。寫入 bool.
type: docs
weight: 326
url: /zh-hant/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) 方法


此屬性指定效果在播放完成後是否會倒帶。寫入 **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的效果序列
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// 取得主序列的第一個效果。
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 開啟效果的 Timing/Rewind。
effect->get_Timing()->set_Rewind(true);
```

## 另請參閱

* 類別 [ITiming](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)