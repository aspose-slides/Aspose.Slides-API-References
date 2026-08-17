---
title: PresentationPlayer
second_title: Aspose.Slides для Java Справка API
description: Представляет проигрыватель анимаций, связанный с .
type: docs
url: /ru/com.aspose.slides/presentationplayer/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
com.aspose.ms.System.IDisposable  
```
public class PresentationPlayer implements System.IDisposable
```

Представляет проигрыватель анимаций, связанный с [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // Воспроизвести анимацию с 33 FPS
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
>          // Воспроизвести анимацию с 45 FPS
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

## Конструкторы

| Constructor | Description |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | Создает новый экземпляр [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
## Методы

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Освобождает экземпляр [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
| [getFrameIndex()](#getFrameIndex--) | Получает индекс кадра. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | Устанавливает новое событие тика кадра. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```

Создает новый экземпляр [PresentationPlayer](../../com.aspose.slides/presentationplayer).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | Генератор анимаций презентации |
| fps | double | Кадров в секунду (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```

Освобождает экземпляр [PresentationPlayer](../../com.aspose.slides/presentationplayer).

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```

Получает индекс кадра.

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

**Возвращает:**  
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```

Устанавливает новое событие тика кадра.

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

Происходит, когда каждый кадр анимации, созданный [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator), генерируется проигрывателем.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | Событие тика кадра. |