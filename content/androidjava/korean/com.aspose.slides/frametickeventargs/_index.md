---
title: FrameTickEventArgs
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: PresentationPlayer.FrameTick 이벤트의 인수를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/frametickeventargs/
---
**상속:**  
java.lang.Object  
```
public class FrameTickEventArgs
```

PresentationPlayer.FrameTick 이벤트의 인수를 나타냅니다.

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

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPlayer()](#getPlayer--) | 프레젠테이션 플레이어를 가져옵니다. |
| [getFrame()](#getFrame--) | 현재 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 프레임을 가져옵니다. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

프레젠테이션 플레이어를 가져옵니다

**반환:**  
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

현재 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 프레임을 가져옵니다.

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


**반환:**  
[IImage](../../com.aspose.slides/iimage)