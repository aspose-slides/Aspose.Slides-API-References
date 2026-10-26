---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
type: docs
url: /pl/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Reprezentuje odtwarzacz animacji.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      {
>          animationsGenerator.setNewAnimation(animationPlayer -> {
>              System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>              animationPlayer.setTimePosition(0);
>              animationPlayer.getFrame().save("firstFrame.png");
> 
>              animationPlayer.setTimePosition(animationPlayer.getDuration());
>              animationPlayer.getFrame().save("lastFrame.png");
>          });
>          animationsGenerator.run(presentation.getSlides());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Animacje generowane przez [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) przy użyciu zdarzenia PresentationAnimationsGenerator.NewAnimation.

## Metody

| Metoda | Opis |
| --- | --- |
| [getDuration()](#getDuration--) | Pobiera czas trwania animacji [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Ustawia pozycję czasu animacji w ramach Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Pobiera klatkę dla bieżącej pozycji czasu wcześniej ustawionej metodą \#setTimePosition(double).setTimePosition(double). |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Pobiera czas trwania animacji [ms]

**Zwraca:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Ustawia pozycję czasu animacji w ramach Duration (\#getDuration.getDuration).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| time | double | Pozycja czasu. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Pobiera klatkę dla bieżącej pozycji czasu wcześniej ustawionej metodą \#setTimePosition(double).setTimePosition(double).

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Obraz klatki