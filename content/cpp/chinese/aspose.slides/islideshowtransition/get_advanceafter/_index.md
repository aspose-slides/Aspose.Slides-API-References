---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API 参考
description: 此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。读取 bool.
type: docs
weight: 105
url: /zh/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() 方法

此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。读取 **bool**。

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 获取第一张幻灯片的过渡
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// 检查是否选中 Advance Slide After 标志
if (slideTransition->get_AdvanceAfter())
{
    // 获取 Advance Slide After 时间值
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 另请参见

* 类 [ISlideShowTransition](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)