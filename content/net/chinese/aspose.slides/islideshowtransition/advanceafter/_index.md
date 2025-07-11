---
title: AdvanceAfter
second_title: Aspose.Sildes for .NET API Reference
description: 此属性指定幻灯片放映是否将在一定时间后移动到下一张幻灯片。可读/可写布尔值。
type: docs
weight: 10
url: /zh/aspose.slides/islideshowtransition/advanceafter/
---

## ISlideShowTransition.AdvanceAfter 属性

此属性指定幻灯片放映是否将在一定时间后移动到下一张幻灯片。可读/可写布尔值。

```csharp
public bool AdvanceAfter { get; set; }
```

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    // 获取第一张幻灯片的过渡
    ISlideShowTransition slideTransition = pres.Slides[0].SlideShowTransition;
    
    // 检查 Advance Slide After 标志是否被选中
    if (slideTransition.AdvanceAfter)
    {
        // 获取 Advance Slide After Time 值
        uint advanceAfterTime = slideTransition.AdvanceAfterTime;
    }
}
```

### 另请参见

* 接口 [ISlideShowTransition](../../islideshowtransition)
* 命名空间 [Aspose.Slides](../../islideshowtransition)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->