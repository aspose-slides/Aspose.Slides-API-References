---
title: PresentationPlayer
second_title: Aspose.Slides for Java API 참조
description: 연관된 애니메이션 플레이어를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/presentationplayer/
---
**상속:**  
java.lang.Object  

**구현된 모든 인터페이스:**  
com.aspose.ms.System.IDisposable  
```
public class PresentationPlayer implements System.IDisposable
```

연관된 [Presentation](../../com.aspose.slides/presentation)와 관련된 애니메이션 플레이어를 나타냅니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // 33 FPS로 애니메이션 재생
>          PresentationPlayer player33 = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player33.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("33fps/frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player33 != null) player33.dispose();
>          }
>          // 45 FPS로 애니메이션 재생
>          PresentationPlayer player45 = new PresentationPlayer(animationsGenerator, 45);
>          try {
>              player45.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("45fps/frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player45 != null) player45.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | 새로운 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [dispose()](#dispose--) | [PresentationPlayer](../../com.aspose.slides/presentationplayer) 인스턴스를 해제합니다. |
| [getFrameIndex()](#getFrameIndex--) | 프레임 인덱스를 반환합니다. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | 새로운 프레임 틱 이벤트를 설정합니다. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```

새로운 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | 프레젠테이션 애니메이션 생성기 |
| fps | double | 초당 프레임 수 (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```

[PresentationPlayer](../../com.aspose.slides/presentationplayer) 인스턴스를 해제합니다.

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```

프레임 인덱스를 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
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

**반환값:**  
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```

새로운 프레임 틱 이벤트를 설정합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
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

--------------------

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)에 의해 생성된 애니메이션의 각 프레임이 플레이어에 의해 생성될 때 발생합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | 프레임 틱 이벤트. |