---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje odtwarzacz animacji.
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

Animacje generowane przez [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) za pośrednictwem zdarzenia PresentationAnimationsGenerator.NewAnimation.

## Metody

| Metoda | Opis |
| --- | --- |
| [getDuration()](#getDuration--) | Pobierz czas trwania animacji [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Ustaw pozycję czasu animacji w obrębie Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Pobierz klatkę dla bieżącej pozycji czasu wcześniej ustawionej metodą \#setTimePosition(double).setTimePosition(double). |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Pobierz czas trwania animacji [ms]

**Zwraca:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Ustaw pozycję czasu animacji w obrębie Duration (\#getDuration.getDuration).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| time | double | Pozycja czasu. |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Pobierz klatkę dla bieżącej pozycji czasu wcześniej ustawionej metodą \#setTimePosition(double).setTimePosition(double).

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Obraz klatki