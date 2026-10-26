---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a player of the animation.
type: docs
url: /nl/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Stelt een speler van de animatie voor.

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

Animaties gegenereerd door [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) via zijn PresentationAnimationsGenerator.NewAnimation gebeurtenis.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDuration()](#getDuration--) | Haal animatieduur op [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Stel de animatietijdpositie in binnen de Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Haal het frame op voor de huidige tijdpositie die eerder is ingesteld met de \#setTimePosition(double).setTimePosition(double) methode. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Haal animatieduur op [ms]

**Retour:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Stel de animatietijdpositie in binnen de Duration (\#getDuration.getDuration).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| time | double | Tijdpositie. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Haal het frame op voor de huidige tijdpositie die eerder is ingesteld met de \#setTimePosition(double).setTimePosition(double) methode.

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Frame afbeelding