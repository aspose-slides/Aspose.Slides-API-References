---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un lettore dell'animazione.
type: docs
url: /it/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Rappresenta un lettore dell'animazione.

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

Animazioni generate da [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) tramite il suo evento PresentationAnimationsGenerator.NewAnimation.
## Metodi

| Method | Descrizione |
| --- | --- |
| [getDuration()](#getDuration--) | Ottieni la durata dell'animazione [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Imposta la posizione temporale dell'animazione all'interno della  Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Ottieni il fotogramma per la posizione temporale corrente precedentemente impostata con il \#setTimePosition(double).setTimePosition(double) method. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Ottieni la durata dell'animazione [ms]

**Restituisce:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Imposta la posizione temporale dell'animazione all'interno della  Duration (\#getDuration.getDuration).

**Parametri:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| time | double | Posizione temporale. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Ottieni il fotogramma per la posizione temporale corrente precedentemente impostata con il \#setTimePosition(double).setTimePosition(double) method.

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Frame image