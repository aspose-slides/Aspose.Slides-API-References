---
title: FrameTickEventArgs
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
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
>              player.setFrameTick((sender, args) -> {
>                  args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              });
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
| [getPlayer()](#getPlayer--) | รับตัวเล่นการนำเสนอ |
| [getFrame()](#getFrame--) | รับเฟรม [PresentationPlayer](../../com.aspose.slides/presentationplayer) ปัจจุบัน. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

รับตัวเล่นการนำเสนอ

**คืนค่า:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

รับเฟรม [PresentationPlayer](../../com.aspose.slides/presentationplayer) ปัจจุบัน.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick((sender, args) -> {
>                  args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              });
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