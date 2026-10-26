---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API 参考
description: 此属性指定幻灯片是否在一定时间后移动到下一张幻灯片。写入 bool.
type: docs
weight: 118
url: /zh/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) 方法


此属性指定幻灯片是否在一定时间后移动到下一张幻灯片。写入 **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 获取第一张幻灯片的过渡
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// 检查是否选中“Advance Slide After”标志
if (slideTransition->get_AdvanceAfter())
{
    // 获取“Advance Slide After”时间值
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 另见

* 类 [SlideShowTransition](../)
* 命名空间 [Aspose::Slides::SlideShow](../../)
* 库 [Aspose.Slides](../../../)