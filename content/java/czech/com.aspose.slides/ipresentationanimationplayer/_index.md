---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
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

Animace generované pomocí [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) prostřednictvím události PresentationAnimationsGenerator.NewAnimation.

## Metody

| Metoda | Popis |
| --- | --- |
| [getDuration()](#getDuration--) | Získá dobu trvání animace [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Nastaví časovou pozici animace v rámci trvání (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Získá snímek pro aktuální časovou pozici dříve nastavenou metodou \#setTimePosition(double).setTimePosition(double). |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Získá dobu trvání animace [ms]

**Vrací:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Nastaví časovou pozici animace v rámci trvání (\#getDuration.getDuration).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| time | double | Časová pozice. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Získá snímek pro aktuální časovou pozici dříve nastavenou metodou \#setTimePosition(double).setTimePosition(double).

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Obrázek snímku