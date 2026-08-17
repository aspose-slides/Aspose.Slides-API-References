---
title: FrameTickEventArgs
second_title: Справочник API Aspose.Slides для Java
description: Представляет аргументы события PresentationPlayer.FrameTick.
type: docs
url: /ru/com.aspose.slides/frametickeventargs/
---
**Наследование:**
java.lang.Object
```
public class FrameTickEventArgs
```

Представляет аргументы события PresentationPlayer.FrameTick.

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
## Методы

| Метод | Описание |
| --- | --- |
| [getPlayer()](#getPlayer--) | Получить проигрыватель презентаций |
| [getFrame()](#getFrame--) | Получить текущий [PresentationPlayer](../../com.aspose.slides/presentationplayer) кадр. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

Получить проигрыватель презентаций

**Возвращаемое значение:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

Получить текущий [PresentationPlayer](../../com.aspose.slides/presentationplayer) кадр.

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


**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage)