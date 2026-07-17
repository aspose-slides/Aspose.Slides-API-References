---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API 参考
description: 此属性指定特效是否会重复直到幻灯片结束。写入 bool。
type: docs
weight: 144
url: /zh/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) 方法


此属性指定特效是否会重复直到幻灯片结束。写入 **bool**。

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// 获取第一张幻灯片的效果序列
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// 获取主序列的第一个效果。
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 将效果的 Timing/Repeat 更改为 "直到幻灯片结束"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 另请参阅

* 类 [ITiming](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)