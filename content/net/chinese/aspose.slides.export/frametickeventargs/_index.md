---
title: FrameTickEventArgs
second_title: Aspose.Sildes for .NET API Reference
description: 表示 FrameTick./presentationplayer/frametick 事件的参数。
type: docs
weight: 3640
url: /zh/aspose.slides.export/frametickeventargs/
---

## FrameTickEventArgs 类

表示 [`FrameTick`](../presentationplayer/frametick) 事件的参数。

```csharp
public class FrameTickEventArgs
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Player](../../aspose.slides.export/frametickeventargs/player) { get; } | 获取演示文稿播放器 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetFrame](../../aspose.slides.export/frametickeventargs/getframe)() | 获取当前 [`PresentationPlayer`](../presentationplayer) 帧。 |

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(pres))
    using (var player = new PresentationPlayer(animationsGenerator, 33))
    {
        int frameNumber = 0;
        player.FrameTick += (sender, args) =>
        {
            args.GetFrame().Save($"frame_{frameNumber++}.png");
        };
        
        animationsGenerator.Run(pres.Slides);
    }
}
```

### 另见

* 命名空间 [Aspose.Slides.Export](../../aspose.slides.export)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->