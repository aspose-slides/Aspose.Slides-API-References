---
title: TransitionDuration
second_title: Aspose.Slides for .NET API 参考
description: 获取或设置缩放和幻灯片之间转换的持续时间 读/写Single 默认值1.0f
type: docs
weight: 60
url: /zh/aspose.slides/izoomobject/transitionduration/
---
## IZoomObject.TransitionDuration property

获取或设置缩放和幻灯片之间转换的持续时间。 读/写Single。 默认值:1.0f

```csharp
public float TransitionDuration { get; set; }
```

### 评论

如果未指定（TransitionDur = 0） ，它将使用目标幻灯片过渡以及与该过渡相关的时间。

### 例子

该示例演示了更改缩放和滑动之间的过渡持续时间:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.TransitionDuration = 2.5f;
}
```

### 也可以看看

* interface [IZoomObject](../../izoomobject)
* 命名空间 [Aspose.Slides](../../izoomobject)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
