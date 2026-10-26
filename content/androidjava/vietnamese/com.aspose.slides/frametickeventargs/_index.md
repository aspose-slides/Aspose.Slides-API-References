---
title: FrameTickEventArgs
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các đối số của sự kiện PresentationPlayer.FrameTick.
type: docs
url: /vi/com.aspose.slides/frametickeventargs/
---
**Kế thừa:**
java.lang.Object
```
public class FrameTickEventArgs
```

Biểu diễn các đối số của sự kiện PresentationPlayer.FrameTick.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Phương thức

| Method | Description |
| --- | --- |
| [getPlayer()](#getPlayer--) | Lấy trình phát bản trình chiếu |
| [getFrame()](#getFrame--) | Lấy khung [PresentationPlayer](../../com.aspose.slides/presentationplayer) hiện tại. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

Lấy trình phát bản trình chiếu

**Trả về:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

Lấy khung [PresentationPlayer](../../com.aspose.slides/presentationplayer) hiện tại.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IImage](../../com.aspose.slides/iimage)