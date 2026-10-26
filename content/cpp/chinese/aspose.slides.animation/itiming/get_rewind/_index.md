---
title: get_Rewind()
second_title: Aspose.Slides for C++ API 参考
description: 此属性指定效果在播放完成后是否会倒回。读取 bool.
type: docs
weight: 313
url: /zh/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() 方法

此属性指定效果在播放完成后是否会倒回。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 获取第一张幻灯片的效果序列
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// 获取主序列的第一个效果。
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 打开效果的 Timing/Rewind。
effect->get_Timing()->set_Rewind(true);
```

## 另见

* 类 [ITiming](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)