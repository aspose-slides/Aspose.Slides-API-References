---
title: get_AdvanceAfter()
second_title: Aspose.Slides C++ API 参考
description: 此属性指定幻灯片放映在一定时间后是否移动到下一张幻灯片。读取 bool。
type: docs
weight: 105
url: /zh/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() 方法

此属性指定幻灯片放映在一定时间后是否移动到下一张幻灯片。读取 **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 获取第一张幻灯片的过渡
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// 检查是否已选中“Advance Slide After”标志
if (slideTransition->get_AdvanceAfter())
{
    // 获取“Advance Slide After Time”值
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 另请参阅

* 类 [SlideShowTransition](../)
* 命名空间 [Aspose::Slides::SlideShow](../../)
* 库 [Aspose.Slides](../../../)