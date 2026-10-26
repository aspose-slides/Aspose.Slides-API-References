---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
type: docs
url: /de/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Stellt einen Player der Animation dar.

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

Von [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) erzeugte Animationen über dessen PresentationAnimationsGenerator.NewAnimation-Ereignis.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDuration()](#getDuration--) | Liefert die Animationsdauer [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Setzt die Animationszeitposition innerhalb der Dauer (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Liefert das Bild für die aktuelle Zeitposition, die zuvor mit der \#setTimePosition(double).setTimePosition(double) Methode gesetzt wurde. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Liefert die Animationsdauer [ms]

**Rückgabewert:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Setzt die Animationszeitposition innerhalb der Dauer (\#getDuration.getDuration).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| time | double | Zeitposition. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Liefert das Bild für die aktuelle Zeitposition, die zuvor mit der \#setTimePosition(double).setTimePosition(double) Methode gesetzt wurde.

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Frame-Bild