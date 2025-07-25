---
title: AdvanceAfter
second_title: Aspose.Sildes for .NET API Reference
description: 该属性指定幻灯片放映在一定时间后是否会移动到下一张幻灯片。可读写布尔值。
type: docs
weight: 10
url: /zh/aspose.slides.slideshow/slideshowtransition/advanceafter/
---

## SlideShowTransition.AdvanceAfter property

该属性指定幻灯片放映在一定时间后是否会移动到下一张幻灯片。可读写布尔值。

```csharp
public bool AdvanceAfter { get; set; }
```

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    // 获取第一张幻灯片的过渡效果
    ISlideShowTransition slideTransition = pres.Slides[0].SlideShowTransition;
    
    // 检查“在之后自动切换幻灯片”标志是否已选中
    if (slideTransition.AdvanceAfter)
    {
        // 获取自动切换幻灯片的时间值
        uint advanceAfterTime = slideTransition.AdvanceAfterTime;
    }
}
```

### 另请参见

* class [SlideShowTransition](../../slideshowtransition)
* namespace [Aspose.Slides.SlideShow](../../slideshowtransition)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->