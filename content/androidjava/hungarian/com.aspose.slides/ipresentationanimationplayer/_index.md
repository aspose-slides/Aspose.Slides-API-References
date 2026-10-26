---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a player of the animation.
type: docs
url: /hu/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Az animáció lejátszóját képviseli.

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

Animációkat generál [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) a PresentationAnimationsGenerator.NewAnimation eseményén keresztül.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getDuration()](#getDuration--) | Animáció időtartamának lekérése [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Az animáció időpozíciójának beállítása a  Duration (\#getDuration.getDuration) belül. |
| [getFrame()](#getFrame--) | Az aktuális időpozícióhoz tartozó keret lekérése, amelyet korábban a \#setTimePosition(double).setTimePosition(double) metódus állított be. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Animáció időtartamának lekérése [ms]

**Visszatér:**  
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Az animáció időpozíciójának beállítása a  Duration (\#getDuration.getDuration) belül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| time | double | Időpozíció. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Az aktuális időpozícióhoz tartozó keret lekérése, amelyet korábban a \#setTimePosition(double).setTimePosition(double) metódus állított be.

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage) - Keret kép