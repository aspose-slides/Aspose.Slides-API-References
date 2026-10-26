---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a player of the animation.
type: docs
url: /sv/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Representerar en spelare av animationen.

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

Animationer genererade av [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) via dess PresentationAnimationsGenerator.NewAnimation-händelse.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDuration()](#getDuration--) | Hämta animationens varaktighet [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Ställ in animationens tidsposition inom varaktigheten (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Hämta ramen för den aktuella tidspositionen som tidigare ställts in med \#setTimePosition(double).setTimePosition(double)-metoden. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Hämta animationens varaktighet [ms]

**Returnerar:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Ställ in animationens tidsposition inom varaktigheten (\#getDuration.getDuration).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| time | double | Tidsposition. |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Hämta ramen för den aktuella tidspositionen som tidigare ställts in med \#setTimePosition(double).setTimePosition(double)-metoden.

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Ram bild