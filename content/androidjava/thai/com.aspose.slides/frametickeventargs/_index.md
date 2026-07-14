---
title: FrameTickEventArgs
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงอาร์กิวเมนต์ของเหตุการณ์ PresentationPlayer.FrameTick
type: docs
url: /th/com.aspose.slides/frametickeventargs/
---
**การสืบทอด:**
java.lang.Object
```
public class FrameTickEventArgs
```

แสดงอาร์กิวเมนต์ของเหตุการณ์ PresentationPlayer.FrameTick

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

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPlayer()](#getPlayer--) | รับผู้เล่นการนำเสนอ |
| [getFrame()](#getFrame--) | รับเฟรม [PresentationPlayer](../../com.aspose.slides/presentationplayer) ปัจจุบัน |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

รับผู้เล่นการนำเสนอ

**คืนค่า:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

รับเฟรม [PresentationPlayer](../../com.aspose.slides/presentationplayer) ปัจจุบัน

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


**คืนค่า:**
[IImage](../../com.aspose.slides/iimage)