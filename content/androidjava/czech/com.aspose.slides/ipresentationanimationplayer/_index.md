---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje přehrávač animace.
type: docs
url: /cs/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Představuje přehrávač animace.

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

Animace generované [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) pomocí jeho události PresentationAnimationsGenerator.NewAnimation event.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDuration()](#getDuration--) | Get animation duration [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Set the animation time position within the  Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Get the frame for the current time position previously set with the \#setTimePosition(double).setTimePosition(double) method. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Získá dobu trvání animace [ms]

**Returns:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Nastaví časovou pozici animace v rámci  Duration (\#getDuration.getDuration).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| time | double | Časová pozice. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Získá snímek pro aktuální časovou pozici dříve nastavenou metodou \#setTimePosition(double).setTimePosition(double) method.

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Obrázek snímku