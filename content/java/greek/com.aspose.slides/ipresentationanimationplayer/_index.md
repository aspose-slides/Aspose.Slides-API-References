---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
type: docs
url: /el/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Αντιπροσωπεύει έναν αναπαραγωγέα της κινούμενης εικόνας.

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

Κινούμενα γραφικά που δημιουργούνται από [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) μέσω του γεγονότος PresentationAnimationsGenerator.NewAnimation event.

## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDuration()](#getDuration--) | Get animation duration [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Ορισμός της θέσης χρόνου animation εντός της Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Get the frame for the current time position previously set with the \#setTimePosition(double).setTimePosition(double) method. |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Get animation duration [ms]

**Επιστρέφει:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Set the animation time position within the  Duration (\#getDuration.getDuration).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| time | double | Θέση χρόνου. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Get the frame for the current time position previously set with the \#setTimePosition(double).setTimePosition(double) method.

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Εικόνα πλαισίου