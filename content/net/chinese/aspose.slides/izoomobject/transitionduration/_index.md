---
title: TransitionDuration
second_title: Aspose.Slides for .NET API Reference
description: 获取或设置缩放与幻灯片之间的过渡持续时间。可读写单精度浮点数。默认值1.0f
type: docs
weight: 50
url: /zh/aspose.slides/izoomobject/transitionduration/
---

## IZoomObject.TransitionDuration 属性

获取或设置缩放与幻灯片之间的过渡持续时间。可读写单精度浮点数。默认值：1.0f

```csharp
public float TransitionDuration { get; set; }
```

### 备注

如果未指定（TransitionDur = 0），则将使用目标幻灯片的过渡效果及其相关时间。

### 示例

该示例演示了如何更改缩放与幻灯片之间的过渡持续时间：

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.TransitionDuration = 2.5f;
}
```

### 另请参阅

* 接口 [IZoomObject](../../izoomobject)
* 命名空间 [Aspose.Slides](../../izoomobject)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->