---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет проигрыватель анимации.
type: docs
url: /ru/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Представляет проигрыватель анимации.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      {
>          animationsGenerator.setNewAnimation(new PresentationAnimationsGenerator.NewAnimation() {
>              public void invoke(IPresentationAnimationPlayer animationPlayer) {
>                  System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>                  animationPlayer.setTimePosition(0);
>                  animationPlayer.getFrame().save("firstFrame.png");
> 
>                  animationPlayer.setTimePosition(animationPlayer.getDuration());
>                  animationPlayer.getFrame().save("lastFrame.png");
>          }});
>          animationsGenerator.run(presentation.getSlides());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Анимации, сгенерированные [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) через его событие PresentationAnimationsGenerator.NewAnimation event.

## Методы

| Method | Description |
| --- | --- |
| [getDuration()](#getDuration--) | Получить длительность анимации [мс] |
| [setTimePosition(double time)](#setTimePosition-double-) | Установить позицию времени анимации в пределах Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Получить кадр для текущей позиции времени, ранее установленной с помощью метода \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Получить длительность анимации [мс]

**Возвращает:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Установить позицию времени анимации в пределах Duration (\#getDuration.getDuration).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| time | double | Позиция времени. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Получить кадр для текущей позиции времени, ранее установленной с помощью метода \#setTimePosition(double).setTimePosition(double).

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - изображение кадра