---
title: TransitionFps
second_title: Aspose.Slides for .NET API 参考
description: 获取或设置过渡 FPS 帧/秒 默认值为 25
type: docs
weight: 50
url: /zh/aspose.slides.export/igifoptions/transitionfps/
---
## IGifOptions.TransitionFps property

获取或设置过渡 FPS [帧/秒] 默认值为 25。

```csharp
public int TransitionFps { get; set; }
```

### 例子

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { TransitionFps = 60 });
}
```

### 也可以看看

* interface [IGifOptions](../../igifoptions)
* 命名空间 [Aspose.Slides.Export](../../igifoptions)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
