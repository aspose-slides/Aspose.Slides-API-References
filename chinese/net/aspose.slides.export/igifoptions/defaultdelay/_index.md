---
title: DefaultDelay
second_title: Aspose.Slides for .NET API 参考
description: 获取或设置默认延迟时间 ms如果AdvanceAfterTimeaspose.slides/islideshowtransition/advanceaftertime未设置将使用此值 默认值为 1000
type: docs
weight: 20
url: /zh/net/aspose.slides.export/igifoptions/defaultdelay/
---
## IGifOptions.DefaultDelay property

获取或设置默认延迟时间 [ms]。如果[`AdvanceAfterTime`](../../../aspose.slides/islideshowtransition/advanceaftertime)未设置，将使用此值。 默认值为 1000。

```csharp
public int DefaultDelay { get; set; }
```

### 例子

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { DefaultDelay = 2000 });
}
```

### 也可以看看

* interface [IGifOptions](../../igifoptions)
* 命名空间 [Aspose.Slides.Export](../../igifoptions)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->