---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides per Android tramite Java API Reference
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

Animazioni generate da [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) tramite il suo evento PresentationAnimationsGenerator.NewAnimation.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDuration()](#getDuration--) | Ottieni la durata dell'animazione [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Imposta la posizione temporale dell'animazione entro la Durata (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Ottieni il fotogramma per la posizione temporale corrente precedentemente impostata con il metodo \#setTimePosition(double).setTimePosition(double). |
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

Imposta la posizione temporale dell'animazione entro la Durata (\#getDuration.getDuration).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| time | double | Posizione temporale. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Ottieni il fotogramma per la posizione temporale corrente precedentemente impostata con il metodo \#setTimePosition(double).setTimePosition(double).

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Immagine del fotogramma