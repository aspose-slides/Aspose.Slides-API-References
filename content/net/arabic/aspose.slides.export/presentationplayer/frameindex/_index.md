---
title: FrameIndex
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يحصل على مؤشر الإطار.
type: docs
weight: 20
url: /ar/aspose.slides.export/presentationplayer/frameindex/
---
## PresentationPlayer.FrameIndex الخاصية

يحصل على مؤشر الإطار.

```csharp
public int FrameIndex { get; }
```

### أمثلة

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(pres))
    using (var player = new PresentationPlayer(animationsGenerator, 33))
    {
        player.FrameTick += (sender, args) =>
        {
            args.GetFrame().Save($"frame_{sender.FrameIndex}.png");
        };
        
        animationsGenerator.Run(pres.Slides);
    }
}
```

### انظر أيضًا

* الفئة [PresentationPlayer](../../presentationplayer)
* النطاق [Aspose.Slides.Export](../../presentationplayer)
* التجميع [Aspose.Slides](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.Slides.dll -->