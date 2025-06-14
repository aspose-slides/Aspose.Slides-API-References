---
title: AfterAnimationColor
second_title: Aspose.Sildes for .NET API Reference
description: 定义效果的动画后颜色。读/写 IColorFormat aspose.slides/icolorformat。
type: docs
weight: 10
url: /zh/aspose.slides.animation/ieffect/afteranimationcolor/
---

## IEffect.AfterAnimationColor 属性

定义效果的动画后颜色。读/写 [`IColorFormat`](../../../aspose.slides/icolorformat)。

```csharp
public IColorFormat AfterAnimationColor { get; set; }
```

### 示例

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // 获取第一张幻灯片的第一个效果。
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // 将效果的动画后类型更改为 "Color"
    firstSlideEffect.AfterAnimationType = AfterAnimationType.Color;
    
    // 设置效果的动画后颜色。
    firstSlideEffect.AfterAnimationColor.Color = Color.Green;
}
```

### 另请参阅

* 接口 [IColorFormat](../../../aspose.slides/icolorformat)
* 接口 [IEffect](../../ieffect)
* 命名空间 [Aspose.Slides.Animation](../../ieffect)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->